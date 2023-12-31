<template>
  <div id="app">
  <router-Link to="/">Home</router-Link>
  <router-Link to="/about">About</router-Link>
    <router-view />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: "App",
  components: {
    // HelloWorld
  },
};
</script>

<style>
/* #app {
  
} */
</style>
