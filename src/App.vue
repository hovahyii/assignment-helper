<template>
  <body>
    <Header />
    <SectionOne />
    <SectionTwo />
    <Services />
    <Price />
    <JoinUs />
  </body>
</template>

<script>
import Header from './components/Header.vue'
import SectionOne from './components/SectionOne.vue'
import SectionTwo from './components/SectionTwo.vue'
import Services from './components/Services.vue'
import Price from './components/Price.vue'
import JoinUs from './components/JoinUs.vue'



export default {
  name: 'App',
  components: {
    Header,
    SectionOne,
    SectionTwo,
    Services,
    Price,
    JoinUs,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
