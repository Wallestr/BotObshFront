<template>
  <div class="app_container">

    <router-view />

    <Nabar />

  </div>
</template>

<script>
  import Navbar from './components/Navbar.vue'

  export default{
    name: 'App',
    components: {
      Navbar
    }
  }
</script>

<style>
  .app_container {
    display: flex;
    flex-direction: column;
    height: 100vh;
    
  }
</style>