<template>
  <body>
    <Section></Section>
    <Section2></Section2>
    <Section3></Section3>
    <Section4></Section4>
    <Section5></Section5>
    <Section6></Section6>
    <Section7></Section7>
    <Section8></Section8>
    <Section9></Section9>
    <Footer></Footer>
  </body>
</template>
<script>

import Section from './section'
import Section2 from './section2'
import Section3 from './section3'
import Section4 from './section4'
import Section5 from './section5'
import Section6 from './section6'
import Section7 from './section7'
import Section8 from './section8'
import Section9 from './section9'
import Footer from './footer'

export default {
  components : {
    Section,
    Section2,
    Section3,
    Section4,
    Section5,
    Section6,
    Section7,
    Section8,
    Section9,
    Footer
  }
}
</script>
<style scoped>
body {
  background: #ffffff;
  margin: 0;
  padding: 0;
  font-family: 'Roboto', sans-serif;
  overflow-x: hidden;
  color: #333333;
}
</style>

