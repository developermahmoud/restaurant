<template>
  <div>
    <div class="secondary pa-10 text-center">
      <h1>إتصل بنا</h1>
    </div>
    <v-container>
      <v-row>
        <v-col cols="12" md="6" sm="12">
          <v-card class="transparent" flat>
            <v-card-title>خدمة عملاء المطعم متوفرة ٢٤ ساعة باليوم</v-card-title>
            <v-card-text>
              <v-form>
                <v-select
                  filled
                  label="الموضوع"
                  :items="['اقتراح', 'مشكلة', 'تواصل']"
                ></v-select>

                <v-text-field filled label="الأسم بالكامل"></v-text-field>
                <v-text-field filled label="البريد الالكترونى"></v-text-field>
                <v-textarea filled label="الرسالة"></v-textarea>
                <v-btn class="primary">إرسال</v-btn>
              </v-form>
            </v-card-text>
          </v-card>
        </v-col>
        <v-col cols="12" md="6" sm="12">
          <v-card class="transparent" flat>
            <v-card-title>بيانات التواصل</v-card-title>
            <v-card-text>
              <v-list class="transparent">
                <v-list-item>
                  <v-list-item-icon
                    ><v-icon>mdi-map-marker</v-icon>
                  </v-list-item-icon>
                  <v-list-item-title
                    >القاهرة, المعادى شارع النصر</v-list-item-title
                  >
                </v-list-item>
                <v-divider></v-divider>
                <v-list-item>
                  <v-list-item-icon
                    ><v-icon>mdi-phone</v-icon>
                  </v-list-item-icon>
                  <v-list-item-title>0231522545</v-list-item-title>
                </v-list-item>
                <v-divider></v-divider>
                <v-list-item>
                  <v-list-item-icon
                    ><v-icon>mdi-cellphone</v-icon>
                  </v-list-item-icon>
                  <v-list-item-title
                    >01111111111 - 01222222222</v-list-item-title
                  >
                </v-list-item>
                <v-divider></v-divider>
                <v-list-item>
                  <v-list-item-icon
                    ><v-icon>mdi-email</v-icon>
                  </v-list-item-icon>
                  <v-list-item-title>admin@restaurants.com</v-list-item-title>
                </v-list-item>
                <v-divider></v-divider>
                <v-list-item>
                  <v-list-item-icon
                    ><v-icon>mdi-fax</v-icon>
                  </v-list-item-icon>
                  <v-list-item-title>0215445455</v-list-item-title>
                </v-list-item>
                <v-divider></v-divider>
              </v-list>
            </v-card-text>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
