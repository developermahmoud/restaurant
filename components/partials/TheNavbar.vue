<template>
  <div>
    <v-app-bar flat app class="bg">
     <v-app-bar-title class="primary--text">المطعم</v-app-bar-title>
        <v-spacer></v-spacer>
        <v-btn link to="/" text>الرئيسية</v-btn>
        <v-btn link to="/contact" text>إتصل بنا</v-btn>
        <v-btn link to="/about" text>من نحن</v-btn>
    </v-app-bar>

    <v-navigation-drawer v-model="drawer" app> </v-navigation-drawer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      drawer: false
    };
  }
};
</script>

<style></style>
