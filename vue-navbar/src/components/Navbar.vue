<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <!-- navbar items, navbar burger... -->
    <app-navbar-items>
      <slot name="s1"></slot>
    </app-navbar-items>
    <app-navbar-burger></app-navbar-burger>
  </div>
</nav>
</template>

<script>
import navbarburger from "./navbar/navbarburger.vue"
import navbaritems from "./navbar/navbaritems.vue"
export default {
  components: {
    'app-navbar-burger': navbarburger,
    'app-navbar-items': navbaritems
  },
  data () {
    return {

    }
  }
}
</script>

<style>

</style>
