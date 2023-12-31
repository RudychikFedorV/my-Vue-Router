<template>
  <div id="app">
  <router-Link to="/">Home</router-Link>
  <router-Link to="/about">About</router-Link>
  <router-Link to="/contacts">Contacts</router-Link>
    <router-view />
  </div>
</template>

<script>

export default {
  name: "App",
  components: {},
};
</script>

<style>

</style>
