<template>
  <div id="app">
      <data-structure></data-structure>
  </div>
</template>

<script>
import DataStructure from './pages/data-structure.vue'

export default {
  name: 'app',
  components: {
    DataStructure
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
    margin-top: 60px;
  }
</style>
