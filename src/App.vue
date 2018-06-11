<template>
  <div id="app">
    <POS />
  </div>
</template>

<script>
import POS from './components/POS'

export default {
  name: 'App',
  components: {
    POS
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
