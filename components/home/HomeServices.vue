<template>
  <v-sheet class="transparent text-center my-10">
    <h1 class="mb-2">اطلب من أكلنى</h1>
    <p>وجبتك المفضلة في 3 خطوات</p>
    <v-row>
      <v-col cols="12" md="4" sm="12">
        <v-card flat class="secondary rounded-xl">
          <v-card-text class="text-center">
            <v-icon x-large>mdi-map-marker-radius-outline</v-icon>
            <h1 class="my-5">حدد موقعك</h1>
            <p>حدد المدينة والمنطقة للوصول لأقرب المطاعم</p>
          </v-card-text>
        </v-card>
      </v-col>
      <v-col cols="12" md="4" sm="12">
        <v-card flat class="secondary rounded-xl">
          <v-card-text class="text-center">
            <v-icon x-large>mdi-food-fork-drink</v-icon>
            <h1 class="my-5">اختر وجبتك</h1>
            <p>اختر وجبتك المفضلة من اكثر من ١٢٠ ألف وجبة في مطاعم مصر</p>
          </v-card-text>
        </v-card>
      </v-col>
      <v-col cols="12" md="4" sm="12">
        <v-card flat class="secondary rounded-xl">
          <v-card-text class="text-center">
            <v-icon x-large>mdi-motorbike</v-icon>
            <h1 class="my-5">استمتع بطعامك</h1>
            <p>استلم وجبتك وادفع عند الاستلام</p>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-sheet>
</template>

<script>
export default {};
</script>

<style></style>
