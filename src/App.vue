<template>
  <div>
    <nav-bar></nav-bar>
    <jumbotron></jumbotron>
    
    <router-view/>
  </div>
</template>

<script>
import Jumbotron from './components/Jumbotron.vue'
import NavBar from './components/NavBar.vue'

export default {
  name: 'App',
  components:{
    NavBar,
    Jumbotron

  }
}
</script>,
    Jumbotron

<style>

</style>
