<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="덕득이는 과자를 너무 좋아해"/>
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

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ff00ff;
  margin-top: 60px;
}
</style>
