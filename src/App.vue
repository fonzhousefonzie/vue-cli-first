<template>
  <div id="app">
    <PrimoTitolo></PrimoTitolo>
    <JumboTron></JumboTron>
  </div>
</template>

<script>
import PrimoTitolo from './components/PrimoTitolo.vue'
import JumboTron from './components/JumboTron.vue'

export default {
  name: 'App',
  components: {
    PrimoTitolo,
    JumboTron,
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
