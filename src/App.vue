<template>
  <h1>JOSE</h1>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <MiComponente titulo="Star Wars"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MiComponente from './components/micomponente.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    MiComponente
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #f80101;
  margin-top: 60px;
}
</style>
