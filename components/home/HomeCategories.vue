<template>
  <div class="secondary my-10 py-10">
    <v-container fluid>
      <div class="text-center">
        <h1 class="mb-2">اختار من أشهر المطاعم</h1>
        <p>وجبتك المفضلة في 3 خطوات</p>
      </div>
      <v-row align="center" justify="center">
        <v-col
          cols="6"
          lg="2"
          xl="2"
          md="2"
          sm="6"
          v-for="(item, i) in items"
          :key="i"
        >
          <v-card flat class="secondary text-center" link to="/restaurants/1">
            <v-card-text>
              <v-avatar size="80">
                <v-img :src="item.src"></v-img>
              </v-avatar>
              <h3 class="mt-2">{{ item.name }}</h3>
            </v-card-text>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          name: "أون ذا جريل - المهندسين",
          src: "https://disdpbee9u48n.cloudfront.net/res/Yb2AluHtAA-1533557800"
        },
        {
          name: "البلكونة",
          src: "https://disdpbee9u48n.cloudfront.net/res/bSNDoOUBNK-1560149942"
        },
        {
          name: "ابو أنس",
          src: "/7rE45aMfZj-1608201525.jpg"
        },
        {
          name: "حرنكش",
          src: "/sDY5BsayEQ-1593100281.jpg"
        },
        {
          name: "أنس الدمشقى",
          src: "/w8lAa6BIeH-1596971734.jpg"
        },
        {
          name: "كامبنيلى",
          src: "/Untitled-71.jpg"
        },
       
      ]
    };
  }
};
</script>

<style></style>
