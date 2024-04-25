<template>
  
  <headerComponent></headerComponent>
  <bodyComponent></bodyComponent>
  <footerComponent></footerComponent>
</template>

<script>

import headerComponent from './components/Header.vue';
import bodyComponent from './components/Body.vue';
import footerComponent from './components/Footer.vue'
export default {
  name: 'App',
  components: {
    headerComponent,
    bodyComponent,
    footerComponent
  }
};
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
