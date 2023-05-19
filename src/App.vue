<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
   <h1>Welcome Anwer chebl</h1>
   <h2>SDI</h2>
   <first msg="Sameh"/>
  </div>
</template>

<script>
import first from './components/First.vue'

export default {
  name: 'App',
  components: {
   first
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
