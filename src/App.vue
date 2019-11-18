<template>
  <div id="app">
      <!-- <data-structure></data-structure> -->
      <swipe></swipe>
  </div>
</template>

<script>
import DataStructure from './pages/data-structure.vue'
import Swipe from './components/swipe/swipe'

export default {
  name: 'app',
  components: {
    DataStructure,
    Swipe
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
