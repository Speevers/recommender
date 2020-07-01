<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to the Recommendation Contraption"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
  #app {
    -webkit-font-smoothing: antialiased;
    text-align: center;
    margin-top: 60px;
  }
</style>
