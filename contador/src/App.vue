<template>
  <div id="app">
    <contaNum/>
  </div>
</template>

<script>
import contaNum from './components/contaNum.vue'

export default {
  name: 'App',
  components: {
    contaNum
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
