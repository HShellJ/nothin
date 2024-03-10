<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <textBox/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import textBox from './components/textBox.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    textBox
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
