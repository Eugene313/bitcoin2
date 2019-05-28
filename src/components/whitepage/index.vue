<template>
  <div class="main">
    <Header></Header>
    <Slider></Slider>
    <Snowboards></Snowboards>
    <Company></Company>
    <Features></Features>
    <Footer></Footer>
  </div>
</template>
<script>
  import Header from './header'
  import Slider from './slider'
  import Snowboards from './snowboards'
  import Company from './company'
  import Features from './features'
  import Footer from './footer'

  export default {
    components : {
      Header,
      Slider,
      Snowboards,
      Company,
      Features,
      Footer
    }
  }
</script>