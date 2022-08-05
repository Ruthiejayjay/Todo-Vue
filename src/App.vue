<template>
  <Navbar />
  <router-view />
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/NavBar.vue'
export default {
  name: 'HomeView',
  components: {
  Navbar
  }
}
</script>

<style>
</style>
