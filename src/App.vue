<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/hello-world.gif">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
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
* {
  background-color: #1c1d1d;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #92dd85;
  margin-top: 60px;
}

p {
  font-size: 1.2rem;
}
</style>
