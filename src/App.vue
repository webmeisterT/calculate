<template>
  <div id="app">
    <CalCulate />
  </div>
</template>

<script>
import CalCulate from './components/CalCulate.vue'

export default {
  name: 'App',
  components: {
    CalCulate
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
  margin-top: 5.5rem;
}
</style>
