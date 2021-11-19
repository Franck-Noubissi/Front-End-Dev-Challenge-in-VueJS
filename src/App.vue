<template>
  <div id="app">
    <front-dev />
  </div>
</template>

<script>
import FrontDev from './components/FrontDev.vue';

export default {
  name: 'App',
  components: {
    FrontDev
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
