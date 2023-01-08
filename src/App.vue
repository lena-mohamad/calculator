<template>
  <div id="app">
    <cal-c />
  </div>
</template>

<script>
import calC from './components/calC.vue'

export default {
  name: 'app',
  components: {
    calC
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
