<template>
  <Navigation />
  <router-view />
</template>

<script>
import Navigation from "./components/Navigation.vue"

export default {
  name: 'App',
  components: {
    Navigation
  }
}
</script>

<style>
body {
  margin: 0px;
  background-image: url("./assets/nebula_1.jpg");
  background-repeat: no-repeat;
  background-size: 100%;
}
</style>
