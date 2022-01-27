<template>
  <div id="app">
    <Header/>
    <Main/>
    <buy-section/>
    <Footer/>
    <sign-section/>
  </div>
</template>

<script>
 import Header from "./components/Header.vue"
 import Main from "./components/Main.vue"
 import BuySection from "./components/BuySection.vue"
 import Footer from "./components/Footer.vue"
 import SignSection from "./components/SignSection.vue"

export default {
  name: 'App',
  components: {
    Header,
    Main,
    BuySection,
    Footer,
    SignSection
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
*{
   margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
</style>
