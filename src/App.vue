<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <h1>簡易的</h1>
    <h2>text</h2>
    <input type="text" pattern="\d*">
    <h2>number</h2>
    <input type="number" pattern="\d*">

    <h1>厳密</h1>
    <h2>text</h2>
    <input type="text" pattern="\d+(\.\d)*">
    <h2>number</h2>
    <input type="number" pattern="\d+(\.\d)*">
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
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
