<template>
  <div>
    <home-parallax />
    <v-container>
      <home-services />
    </v-container>
    <home-categories />
  </div>
</template>

<script>
import HomeCategories from '../components/home/HomeCategories.vue';
import HomeParallax from '../components/home/HomeParallax.vue';
import HomeServices from '../components/home/HomeServices.vue';
export default {
  components: { HomeParallax, HomeServices, HomeCategories },};
</script>
