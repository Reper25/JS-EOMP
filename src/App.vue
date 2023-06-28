<template>
  <navbarComp/>
  <home/>
  <footercomp />
  <!-- <router-view/> -->
</template>
<script>
import home from './components/Home-comp.vue';
import navbarComp from './components/navbar-comp.vue';
import footercomp from './components/footer-comp.vue';
export default {
  components: {home, navbarComp, footercomp }
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
