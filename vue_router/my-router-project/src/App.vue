<template>
  <div id="app">
    testsete
    <div id="nav">
      <router-link :to="{name : 'Home'}">Home</router-link> |
      <router-link :to="{name : 'About'}">About</router-link> |
      <router-link to="/user/radit">User</router-link> 
    </div>
    <router-view/>
  </div>
</template>

<script>

export default {
  name: 'App'
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
