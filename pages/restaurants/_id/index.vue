<template>
  <div>
    <div class="secondary py-5">
      <v-container>
        <v-row>
          <v-col cols="12" md="4" sm="12">
            <v-row>
              <v-col cols="3">
                <v-avatar size="120">
                  <v-img
                    src="https://disdpbee9u48n.cloudfront.net/res/bSNDoOUBNK-1560149942"
                  />
                </v-avatar>
              </v-col>
              <v-col cols="9">
                <v-card flat class="transparent">
                  <v-card-title class="mt-0 pt-0">البلكونة</v-card-title>
                  <div class="d-flex">
                    <v-rating
                      class="mr-2"
                      value="20"
                      background-color="white"
                      color="yellow accent-4"
                      dense
                      half-increments
                      hover
                      size="18"
                    ></v-rating>
                    <span> ( 25 تعليق )</span>
                  </div>
                  <div class="mr-2 mt-5">
                    <v-chip small color="primary">ديلفرى</v-chip>
                    <v-chip small color="primary">الاستلام من المطعم</v-chip>
                  </div>
                  <div class="mr-2 mt-5">
                    <v-icon>mdi-map-marker</v-icon> ١٤ شارع يلبغا - شبرا -
                    القاهرة
                  </div>
                </v-card>
              </v-col>
            </v-row>
          </v-col>
          <v-col cols="12" md="8" sm="12">
            <v-row>
              <v-col cols="12" md="4" sm="12">
                <v-card flat class="transparent">
                  <v-list-item>
                    <v-list-item-icon
                      ><v-icon large>mdi-clipboard</v-icon></v-list-item-icon
                    >
                    <v-list-item-content>
                      <v-list-item-title>حالة المطعم</v-list-item-title>
                      <v-list-item-subtitle
                        ><span class="red--text"
                          >مشغول</span
                        ></v-list-item-subtitle
                      >
                    </v-list-item-content>
                  </v-list-item>
                </v-card>
              </v-col>
              <v-col cols="12" md="4" sm="12">
                <v-card flat class="transparent">
                  <v-list-item>
                    <v-list-item-icon
                      ><v-icon large
                        >mdi-timer-sand-empty</v-icon
                      ></v-list-item-icon
                    >
                    <v-list-item-content>
                      <v-list-item-title>وقت التوصيل</v-list-item-title>
                      <v-list-item-subtitle>60 دقيقة </v-list-item-subtitle>
                    </v-list-item-content>
                  </v-list-item>
                </v-card>
              </v-col>
              <v-col cols="12" md="4" sm="12">
                <v-card flat class="transparent">
                  <v-list-item>
                    <v-list-item-icon
                      ><v-icon large>mdi-clock</v-icon></v-list-item-icon
                    >
                    <v-list-item-content>
                      <v-list-item-title>بداية العمل</v-list-item-title>
                      <v-list-item-subtitle>الثامنة صباحا</v-list-item-subtitle>
                    </v-list-item-content>
                  </v-list-item>
                </v-card>
              </v-col>
              <v-col cols="12" md="4" sm="12">
                <v-card flat class="transparent">
                  <v-list-item>
                    <v-list-item-icon
                      ><v-icon large>mdi-cart</v-icon></v-list-item-icon
                    >
                    <v-list-item-content>
                      <v-list-item-title>الحد الأدنى للطلب </v-list-item-title>
                      <v-list-item-subtitle>10 جنيه</v-list-item-subtitle>
                    </v-list-item-content>
                  </v-list-item>
                </v-card>
              </v-col>
              <v-col cols="12" md="4" sm="12">
                <v-card flat class="transparent">
                  <v-list-item>
                    <v-list-item-icon
                      ><v-icon large>mdi-cash-100</v-icon></v-list-item-icon
                    >
                    <v-list-item-content>
                      <v-list-item-title>رسوم التوصيل </v-list-item-title>
                      <v-list-item-subtitle>30 جنيه</v-list-item-subtitle>
                    </v-list-item-content>
                  </v-list-item>
                </v-card>
              </v-col>
              <v-col cols="12" md="4" sm="12">
                <v-card flat class="transparent">
                  <v-list-item>
                    <v-list-item-icon
                      ><v-icon large
                        >mdi-clock-time-ten-outline</v-icon
                      ></v-list-item-icon
                    >
                    <v-list-item-content>
                      <v-list-item-title>نهاية العمل </v-list-item-title>
                      <v-list-item-subtitle>العاشرة مساءا</v-list-item-subtitle>
                    </v-list-item-content>
                  </v-list-item>
                </v-card>
              </v-col>
            </v-row>
          </v-col>
        </v-row>
      </v-container>
    </div>
    <v-container>
      <v-row>
        <v-col cols="12" md="2" sm="12">
          <v-list class="secondary py-0" rounded dense>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>حلويات</v-list-item-title>
              </v-list-item-content>
              <v-list-item-action>
                <v-icon>mdi-chevron-left</v-icon>
              </v-list-item-action>
            </v-list-item>
            <v-divider></v-divider>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>الطواجن</v-list-item-title>
              </v-list-item-content>
              <v-list-item-action>
                <v-icon>mdi-chevron-left</v-icon>
              </v-list-item-action>
            </v-list-item>
            <v-divider></v-divider>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>الوافل</v-list-item-title>
              </v-list-item-content>
              <v-list-item-action>
                <v-icon>mdi-chevron-left</v-icon>
              </v-list-item-action>
            </v-list-item>
            <v-divider></v-divider>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>البرطمانات</v-list-item-title>
              </v-list-item-content>
              <v-list-item-action>
                <v-icon>mdi-chevron-left</v-icon>
              </v-list-item-action>
            </v-list-item>
            <v-divider></v-divider>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>العصائر</v-list-item-title>
              </v-list-item-content>
              <v-list-item-action>
                <v-icon>mdi-chevron-left</v-icon>
              </v-list-item-action>
            </v-list-item>
            <v-divider></v-divider>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>السموزى</v-list-item-title>
              </v-list-item-content>
              <v-list-item-action>
                <v-icon>mdi-chevron-left</v-icon>
              </v-list-item-action>
            </v-list-item>
            <v-divider></v-divider>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>المشويات</v-list-item-title>
              </v-list-item-content>
              <v-list-item-action>
                <v-icon>mdi-chevron-left</v-icon>
              </v-list-item-action>
            </v-list-item>
            <v-divider></v-divider>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>شوربة</v-list-item-title>
              </v-list-item-content>
              <v-list-item-action>
                <v-icon>mdi-chevron-left</v-icon>
              </v-list-item-action>
            </v-list-item>
          </v-list>
        </v-col>
        <v-col cols="12" md="7" sm="12">
          <v-card class="secondary rounded-lg" flat>
            <v-card-title>
              قائمة الطعام
            </v-card-title>
            <v-divider></v-divider>
            <v-subheader>الحلويات</v-subheader>
            <v-card-text>
                <v-img src="https://disdpbee9u48n.cloudfront.net/categories/%D8%AD%D9%84%D9%88%D9%8A%D8%A7%D8%AA1.jpg"></v-img>
            </v-card-text>
            <v-card-text>
                 <v-simple-table class="transparent">
              <template v-slot:default>
                <thead>
                  <tr>
                    <th>
                      الصنف / الوجبة
                    </th>
                    <th>
                      السعر
                    </th>
                    <th>
                      اطلب
                    </th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td class="pa-2">
                      <v-avatar>
                        <v-img
                          src="https://disdpbee9u48n.cloudfront.net/res/bSNDoOUBNK-1560149942"
                        ></v-img>
                      </v-avatar>
                      دونتس
                    </td>
                    <td>13 جـ</td>
                    <td>
                      <v-btn icon>
                        <v-icon color="primary">mdi-plus-circle</v-icon>
                      </v-btn>
                    </td>
                  </tr>
                  <tr>
                    <td class="pa-2">
                      <v-avatar>
                        <v-img
                          src="https://disdpbee9u48n.cloudfront.net/res/bSNDoOUBNK-1560149942"
                        ></v-img>
                      </v-avatar>
                      كب كيك
                    </td>
                    <td>60 جـ</td>
                    <td>
                      <v-btn icon>
                        <v-icon color="primary">mdi-plus-circle</v-icon>
                      </v-btn>
                    </td>
                  </tr>
                  <tr>
                    <td class="pa-2">
                      <v-avatar>
                        <v-img
                          src="https://disdpbee9u48n.cloudfront.net/res/bSNDoOUBNK-1560149942"
                        ></v-img>
                      </v-avatar>
                      براونيز آيس كريم
                    </td>
                    <td>40 جـ</td>
                    <td>
                      <v-btn icon>
                        <v-icon color="primary">mdi-plus-circle</v-icon>
                      </v-btn>
                    </td>
                  </tr>
                  <tr>
                    <td class="pa-2">
                      <v-avatar>
                        <v-img
                          src="https://disdpbee9u48n.cloudfront.net/res/bSNDoOUBNK-1560149942"
                        ></v-img>
                      </v-avatar>
                      مولتن كيك
                    </td>
                    <td>30 جـ</td>
                    <td>
                      <v-btn icon>
                        <v-icon color="primary">mdi-plus-circle</v-icon>
                      </v-btn>
                    </td>
                  </tr>
                  <tr>
                    <td class="pa-2">
                      <v-avatar>
                        <v-img
                          src="https://disdpbee9u48n.cloudfront.net/res/bSNDoOUBNK-1560149942"
                        ></v-img>
                      </v-avatar>
                      ديسباسيتو
                    </td>
                    <td>15 جـ</td>
                    <td>
                      <v-btn icon>
                        <v-icon color="primary">mdi-plus-circle</v-icon>
                      </v-btn>
                    </td>
                  </tr>
                  <tr>
                    <td class="pa-2">
                      <v-avatar>
                        <v-img
                          src="https://disdpbee9u48n.cloudfront.net/res/bSNDoOUBNK-1560149942"
                        ></v-img>
                      </v-avatar>
                      سينابون
                    </td>
                    <td>20 جـ</td>
                    <td>
                      <v-btn icon>
                        <v-icon color="primary">mdi-plus-circle</v-icon>
                      </v-btn>
                    </td>
                  </tr>
                  <tr>
                    <td class="pa-2">
                      <v-avatar>
                        <v-img
                          src="https://disdpbee9u48n.cloudfront.net/res/bSNDoOUBNK-1560149942"
                        ></v-img>
                      </v-avatar>
                      أكليريكو
                    </td>
                    <td>30 جـ</td>
                    <td>
                      <v-btn icon>
                        <v-icon color="primary">mdi-plus-circle</v-icon>
                      </v-btn>
                    </td>
                  </tr>
                  <tr>
                    <td class="pa-2">
                      <v-avatar>
                        <v-img
                          src="https://disdpbee9u48n.cloudfront.net/res/bSNDoOUBNK-1560149942"
                        ></v-img>
                      </v-avatar>
                      شوكو سربرايز
                    </td>
                    <td>100 جـ</td>
                    <td>
                      <v-btn icon>
                        <v-icon color="primary">mdi-plus-circle</v-icon>
                      </v-btn>
                    </td>
                  </tr>
                </tbody>
              </template>
            </v-simple-table>
            </v-card-text>
            
           
          </v-card>
        </v-col>
        <v-col cols="12" md="3" sm="12">
          <v-card class="secondary rounded-lg" flat>
            <v-card-title>
              الطلبات
              <v-spacer></v-spacer>
              <v-icon>mdi-cart</v-icon>
            </v-card-title>
            <v-divider></v-divider>
            <v-card-text class="text-center">
              <h2 class="mt-10 mb-7">قائمة الطلبات فارغة</h2>
              <v-icon size="90" color="grey">mdi-cart-off</v-icon>
            </v-card-text>
            <v-card-text class="text-center">
              <v-btn outlined color="primary"
                ><v-icon>mdi-heart-outline</v-icon>أضف إلى المفضلة</v-btn
              >
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
