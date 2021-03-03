<template>
  <v-app dark>
    <the-navbar />
    <v-main class="bg">
        <nuxt />
    </v-main>
    <the-footer />
  </v-app>
</template>

<script>
import TheFooter from '../components/partials/TheFooter.vue'
import TheNavbar from '../components/partials/TheNavbar.vue'
export default {
  components: { TheNavbar, TheFooter },
}
</script>
