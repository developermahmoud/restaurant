<template>
  <v-parallax src="/landing-bg-min.jpeg">
      <v-row>
        <v-row class="pa-4" align="center" justify="center">
          <v-card width="400" class="secondary rounded-xl pa-5" style="opacity: 0.8;">
            <v-card-text class="text-center">
              <h1 class="primary--text mb-10">الأكل اللى نفسك فيه</h1>
              <div class="d-flex justify-center justify-space-between">
                <v-text-field filled tile label="اختر مدينتك" prepend-inner-icon="mdi-map-marker"></v-text-field>
                <v-text-field filled tile label="اختر منطقتك" prepend-inner-icon="mdi-home"></v-text-field>
              </div>
            </v-card-text>
            <v-card-text class="text-center">
              <v-btn class="primary" x-large text rounded width="300">عرض المطاعم</v-btn>
            </v-card-text>
          </v-card>
        </v-row>
      </v-row>
    </v-parallax>
</template>

<script>
export default {

}
</script>

<style>

</style>