<template>
  <div id="app">
    <Hero/>
  </div>
</template>

<script>

import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    Hero,
  }
}
</script>

<style lang="scss">
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

#app {
  @import url('https://fonts.googleapis.com/css2?family=Koh+Santepheap:wght@300&display=swap');
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>