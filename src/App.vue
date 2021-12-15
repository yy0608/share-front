<template>
  <div id="app">
    <!-- <img src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <div class="reveal">
      <div class="slides">
        <page1 />
        <page2 />
        <page3 />
        <page4 />
      </div>
    </div>
  </div>
</template>

<script>
import Reveal from 'reveal.js/js/reveal';
// import highlight from 'reveal.js/plugin/highlight/highlight.js'
import { Page1, Page2, Page3, Page4 } from './components'

export default {
  mounted() {
    Reveal.initialize({
      slideNumber: true
      // plugins: [highlight]
    });
  },
  components: {
    Page1, Page2, Page3, Page4
  }
};
</script>

<style scoped>
@import url('../node_modules/reveal.js/css/reveal.css');
@import url('../node_modules/reveal.js/css/theme/black.css');

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
  height: 100vh;
}
</style>
