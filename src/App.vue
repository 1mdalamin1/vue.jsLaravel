<template>
  <!-- <v-app>
    <app-navigation />
    <v-content transition="slide-x-transition">
      <router-view></router-view>
    </v-content>
  </v-app> -->
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">  -->
    <AppNavigation />
    <Promo />
    <NewInterior />
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
import AppNavigation from './components/AppNavigation.vue'
import NewInterior from './components/NewInterior.vue'
import Promo from './components/Promo.vue'
// import HelloWorld from './components/AppNavigation.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    AppNavigation,
    Promo,
    NewInterior
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
