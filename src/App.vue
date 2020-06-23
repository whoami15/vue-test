<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <h1>Hello mga Ka-Lockdown</h1>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  },
  created () {
    document.title = "Mga Ka-Lockdown";
  }
}
</script>

<style>
@import './assets/css/style.css';
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
