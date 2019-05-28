<template>
  <footer>
  <div class="row">
    <div class="region">
      <p>© 2019 Mountains Snowboards</p>
    </div>
  </div>
</footer>
</template>
<style lang="sass" scoped>
  footer
    background: #000000
    width: 100%
    height: 100px
    display: flex
    justify-content: center
    align-items: center
    @media (max-width:770px)
        padding: 73px 30px
    @media (max-width:640px)
        padding: 15px 15px 40px
    .row
        width: 100%
        max-width: 960px
        display: flex
        justify-content: center
        color:#ffffff
        .region
           width: 100%
           display: flex
           justify-content: center
</style>

