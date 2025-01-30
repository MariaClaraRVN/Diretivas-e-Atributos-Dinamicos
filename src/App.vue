<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld/>
  <ArgumentosLinks/>
</template>

<script>
import ArgumentosLinks from './components/ArgumentosLinks.vue';
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld ,
    ArgumentosLinks ,
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
