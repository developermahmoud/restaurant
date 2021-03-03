<template>
  <v-footer
    color="bg"
    class="pt-7"
    padless
  >
    <v-row
      justify="center"
    >
      <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4 white--text"
          icon
        >
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
      <v-col
        class="bg py-4 text-center white--text"
        cols="12"
      >
        {{ new Date().getFullYear() }} — <strong>المطعم</strong>
      </v-col>
    </v-row>
  </v-footer>
</template>
<script>
  export default {
    data: () => ({
      icons: [
        'mdi-facebook',
        'mdi-twitter',
        'mdi-linkedin',
        'mdi-instagram',
      ],
    }),
  }
</script>