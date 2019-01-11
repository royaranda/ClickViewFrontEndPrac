<template>
  <div id="app">
    <Videos />
  </div>
</template>

<script>
import Videos from './components/Videos.vue'

export default {
  name: 'app',
  components: {
    Videos
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
