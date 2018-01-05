<template>
    <app-navbar-item></app-navbar-item>
</template>

<script>
import navbaritem from "./navbaritem.vue"
export default {
  components: {
    'app-navbar-item': navbaritem
  },
  data () {
    return {
      data: 'TEST'
    }
  }
}
</script>

<style>

</style>
