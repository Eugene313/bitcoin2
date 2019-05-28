<template>
  <div id="app">
    <whitepage v-if="country"></whitepage>
    <bitcoinpage v-else v-show="bitcoin"></bitcoinpage>
  </div>
</template>
<script>
export default {
  name : 'index',
  data () {
    return {
      country : false,
      ipData : null,
      bitcoin: false
    }
  },
  beforeCreate () {
    fetch('http://free.ipwhois.io/json/')
    .then(resp => resp.json())
    .then(json => this.ipData = json.country)
    .then( () => {
      console.log(this.ipData)
      if (this.ipData === 'United States' || this.ipData === 'India') {
        this.country = true
      } else {
        this.bitcoin = true
      }
    })
  }

}
</script>
<style lang="sass">
*
    margin: 0
    padding: 0
    box-sizing: border-box
    font-family: sans-serif
    font-weight: 300
.main
    overflow hidden
</style>



