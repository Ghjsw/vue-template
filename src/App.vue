<template>
  <div id="app">
   <BuildComp />
  </div>
</template>

<script>
import BuildComp from './components/build/index.vue';

export default {
  name: 'App',
  components: {
    BuildComp
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
