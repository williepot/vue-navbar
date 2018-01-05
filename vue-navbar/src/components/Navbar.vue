<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <!-- navbar items, navbar burger... -->
    <app-navbar-menu></app-navbar-menu>
    <app-navbar-burger></app-navbar-burger>
  </div>
</nav>
</template>

<script>
import navbarburger from "./navbar/navbarburger.vue"
import navbarmenu from "./navbar/navbarmenu.vue"
export default {
  components: {
    'app-navbar-burger': navbarburger,
    'app-navbar-menu': navbarmenu
  },
  data () {
    return {

    }
  }
}
</script>

<style>

</style>
