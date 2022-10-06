<template>
  <div id="app">
    <img
      alt="Vue logo"
      src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c2/Adobe_XD_CC_icon.svg/250px-Adobe_XD_CC_icon.svg.png"
      
    />
    <HelloWorld msg=" Welcome to Your Vue.js App" />
    <img
          alt="Vue"
      src="https://image.shutterstock.com/image-vector/vector-creative-illustration-cosmonaut-spacesuit-600w-1680589189.jpg"
    />
    <HelloWorld msg=" Las tecnologías Web son lo Máximo" />

  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
};
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
