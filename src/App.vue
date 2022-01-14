<template>
  <div id="app">
    <Nav />
    <LandingPage msg="Welcome to Unsplash app built with Vue"/>
  </div>
</template>

<script>
import LandingPage from './components/LandingPage.vue';
import Nav from "./components/Nav.vue";

export default {
  name: 'App',
  components: {
    Nav,
    LandingPage
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
  margin: 0 auto;

  /* margin: 0 auto; */
  /* border: 2px solid red; */
}
</style>
