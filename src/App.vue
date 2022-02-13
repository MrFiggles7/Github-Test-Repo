<template>
  <div id="app">
    <Casidy></Casidy>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <img alt="Vue logo" src="./assets/logo.png">
    <Button></Button>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Casidy from "@/components/Casidy";
import Button from "@/components/Button";

export default {
  name: 'App',
  components: {
    HelloWorld,
    Casidy,
    Button,
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
