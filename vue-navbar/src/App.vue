<template>
  <div id="app">
    <app-navbar></app-navbar>
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue"
export default {
  components: {
    'app-navbar': Navbar
  },
  data () {
    return {

    }
  }
}
</script>

<style>

</style>
