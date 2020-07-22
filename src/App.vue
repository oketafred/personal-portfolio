<template>
  <div id="app">
    <nav-bar/>
    <home/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Home from './views/Home.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    Home
  }
}
</script>

<style>

</style>
