<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <img src="./img/test.jpg" alt="" width="30%">
    <Home/>
    <back-to-top text="Back to top"></back-to-top>
    <!-- <FooterAmicale/> -->
  </div>
</template>

<script>
import Home from './components/Home.vue'
import BackToTop from 'vue-backtotop'
// import FooterAmicale from './components/FooterAmicale.vue'
export default {
  name: 'App',
  components: {
    Home,
    BackToTop
    // FooterAmicale
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
  /*background-color: #c3e3f7;*/
}
#app .vue-back-to-top {
  width: 100px;
  background-color: #c7c6d3;
  bottom: 15px;
  right: 75px;
}
</style>
