<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Title />
    <img src="https://wips.plug.it/cips/tecnologia/cms/2021/08/mondo.jpg" alt="Mondo">
  </div>
</template>

<script>
import Title from './components/Title.vue'

export default {
  name: 'App',
  components: {
    Title
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
