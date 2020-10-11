<template>
  <div id="app">
    <edcs msg="Willkommen zur Clauss Slaby Transformation." />
  </div>
</template>


<script>

import edcs from './components/edcs.vue'

export default {
  name: 'App',
  components: {
    edcs
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
