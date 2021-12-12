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
// import Markdown from 'reveal.js/plugin/markdown/markdown.esm.js'
import { Page1, Page2, Page3, Page4 } from './components'

export default {
  mounted() {
    // for (const key in deck) {
    //   console.log(key)
    // }
    // setTimeout(() => {
    //   Reveal.initialize()
    // }, 2000)

    Reveal.initialize({
      slideNumber: true
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
