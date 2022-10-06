<template>
  <div id="app">
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png">
    <HelloWorld msg=" Mirko was here XD to Your Vue.js App"/>
    <HelloWorld msg=" Hola mundo cruel"/>
    
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
