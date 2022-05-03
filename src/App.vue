<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MainTitle />
    <mainParagraph />
  </div>
</template>

<script>
import MainTitle from './components/MainTitle.vue'
import mainParagraph from './components/mainParagraph.vue'
export default {
  name: 'App',
  components: { 
    MainTitle,
    mainParagraph
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
