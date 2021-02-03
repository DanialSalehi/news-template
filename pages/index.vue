<template>
  <v-row justify="center" align="center">
    <v-col>
      <v-sheet class="pa-1" outlined>
        <v-card class="pa-1 d-flex flex-row" outlined height="30">
          <div id="nav" class="d-flex justify-center">
            <router-link to="/">Home</router-link> |
            <router-link to="/about">About</router-link>|
            <router-link to="/">Home</router-link> |
            <router-link to="/about">About</router-link>|
          </div>
          <v-spacer />
          <v-spacer />

          <v-row md6 class="mr-5">
            <v-icon class="pa-1">mdi-email</v-icon>
            <v-icon class="pa-1">mdi-email</v-icon>
            <v-icon class="pa-1">mdi-email</v-icon>
            <v-icon class="pa-1">mdi-email</v-icon>
          </v-row>

          <span>به روز شده در: ۱۴ بهمن ۱۳۹۹ - ۱۲:۱۹</span>
        </v-card>
        <br />
        <v-row justify="center" class="">
          <v-flex md6 class="ml-3">
            <v-sheet class="pa-1 rounded-lg" elevation="2" height="150">
              <span>سلام بر شما همکار عزیز</span>
              <br />
              <br />
              <v-row class="px-4">
                <v-img
                  contain
                  md3
                  src="https://asriran.com/files/fa/logo/110_454.gif"
                ></v-img>
                <v-img
                  md3
                  src="https://asriran.com/files/fa/logo/110_454.gif"
                ></v-img>
              </v-row>
            </v-sheet>
            <v-sheet height="30" class="pa-1 rounded-lg mt-2" elevation="1">
            </v-sheet>
            <v-sheet
              height="150"
              class="pa-1 rounded-lg mt-2 d-flex"
              elevation="1"
            >
              <v-card class="d-flex align-center mb-6" flat height="130" tile>
                <v-img
                  contain
                  width="185"
                  height="100"
                  src="https://cdn.asriran.com/files/fa/news/1399/11/14/1182050_148.jpg"
                ></v-img>
                <v-col cols="7">
                  <v-row class="mt-1"><h3>salam</h3> </v-row>
                  <v-row class="pa-1">
                    <h5>
                      واقعا برگزاری جشنواره فجر با حضور تماشاگران آنقدر مهم بود؟
                      الان تماشگر فوتبال حق ندارد بگوید، چرا به ما اجازه
                      نمی‌دهید فوتبال‌ها را نگاه کنیم؟ ستاد ملی مبارزه با کرونا،
                      راه را یاد گرفته است و وقتی تقی به توقی می‌خورد، پای مردم
                      را وسط می‌کشند و آنها را مقصر جلوه می‌دهند. الان هم انگار
                      مردم مقصر حضوری شدن جشنواره فیلم فجر هستند!
                    </h5></v-row
                  >
                </v-col>
              </v-card>
            </v-sheet>
            <v-sheet class="pa-1 rounded-lg mt-2" elevation="1">
              <div class="d-flex flex-culomn justify-space-around">
                <div>
                  <v-card
                    flat
                    class="pa-1 d-flex flex-row ma-1"
                    v-for="x in 10"
                    :key="x"
                    height="140"
                  >
                    <v-col cols="8">
                      <h4>وعدۀ آب و برق مجانی؟</h4>
                      <h5>
                        اصل وعدۀ آب و برق رایگان درست است اما اولا نه برای همه
                        که برای کم درآمدها.
                      </h5>
                    </v-col>
                    <v-img
                      contain
                      src="https://cdn.asriran.com/files/fa/news/1399/11/14/1182052_329.jpg"
                    ></v-img>
                  </v-card>
                </div>
                <div>
                  <v-card
                    flat
                    class="pa-1 d-flex flex-row ma-1"
                    v-for="x in 10"
                    :key="x"
                    height="140"
                  >
                    <v-col cols="8">
                      <h4>وعدۀ آب و برق مجانی؟</h4>
                      <h5>
                        اصل وعدۀ آب و برق رایگان درست است اما اولا نه برای همه
                        که برای کم درآمدها.
                      </h5>
                    </v-col>
                    <v-img
                      contain
                      src="https://cdn.asriran.com/files/fa/news/1399/11/14/1182052_329.jpg"
                    ></v-img>
                  </v-card>
                </div>
              </div>
            </v-sheet>
          </v-flex>
          <v-flex class="ma-1" md3>
            <v-text-field
              label="جستوجو در سایت"
              outlined
              dense
              append-icon="mdi-magnify"
            />
            <v-row justify="center">
              <v-card outlined>
                <v-btn class="mx-1" small text v-for="x in 4" :key="x">
                  click
                </v-btn>
              </v-card>
            </v-row>
            <br />

            <v-img
              v-for="x in 4"
              :key="x"
              src="https://cdn.asriran.com/files/adv/6226_952.gif"
              class="my-1"
            ></v-img>

            <br />
            <div class="d-flex flex-culomn justify-center">
              <div class="d-flex flex-row justify-center">
                <v-sheet
                  outlined
                  class="d-flex mx-1 justify-center align-center rounded-t-lg"
                  height="53"
                  width="87"
                  ><h4>ویژه ها</h4>
                </v-sheet>

                <v-sheet
                  class="d-flex lighten-1 rounded-t-lg"
                  height="53"
                  width="200"
                  outlined
                >
                  <v-col class="mt-1">
                    <v-row justify="center">پربازدید ها</v-row>
                    <v-row justify="center">
                      <v-sheet
                        outlined
                        height="24"
                        width="25%"
                        class="d-flex justify-space-around grey lighten-1 rounded-t-lg"
                        >روز</v-sheet
                      >
                      <v-sheet
                        outlined
                        height="24"
                        width="25%"
                        class="d-flex justify-space-around grey lighten-1 rounded-t-lg"
                        >روز</v-sheet
                      >
                      <v-sheet
                        outlined
                        height="24"
                        width="25%"
                        class="d-flex justify-space-around grey lighten-1 rounded-t-lg"
                        >روز</v-sheet
                      >
                      <v-sheet
                        outlined
                        height="24"
                        width="25%"
                        class="d-flex justify-space-around pa-0 grey lighten-1 rounded-t-lg"
                        >روز</v-sheet
                      >
                    </v-row>
                  </v-col>
                </v-sheet>
              </div>
            </div>
            <div class="d-flex flex-culomn justify-center">
              <v-sheet width="100%" elevation="1" class="pa-1 ma-1">
                <div v-for="x in 8" class="py-1" :key="x">
                  <h5>
                    <v-icon color="red">mdi-pan-bottom-left</v-icon>
                    مخالفت فراکسیون زنان با لغو مجازات زندان برای مهریه بیش از ۵
                    سکه/در طرح مجلس فقط مردها دیده شده‌اند
                  </h5>
                </div>
              </v-sheet>
            </div>
            <div class="py-1" />
            <v-sheet class="rounded" elevation="2" width="100%">
              <v-sheet
                class="rounded-t grey lighten-1"
                outlined
                height="30"
                width="100%"
                ><span class="indigo--text mr-2">نظرسنجی</span>
              </v-sheet>
              <v-col>
                <span>
                  اگر بتوانید، آیا به کشوری مانند کانادا مهاجرت می کنید؟
                </span>
                <div>
                  <v-radio-group v-model="radioGroup">
                    <v-radio label="بله" :value="n"></v-radio>
                    <v-radio label="خیر" :value="n"></v-radio>
                  </v-radio-group>
                  <v-btn class="rounded" outlined>ثبت رای</v-btn>
                </div>
              </v-col>
            </v-sheet>
            <v-img
              class="mt-3"
              src="https://mostatil.yektanet.com/media/300x100_resize.gif"
              width="100%"
              contain
            ></v-img>
            <v-img
              class="mt-3"
              src="https://mostatil.yektanet.com/media/300x250_S3kaKKD.gif"
              width="100%"
            ></v-img>
            <v-sheet outlined class="pa-1 my-2 rounded-b" width="100%">
              <v-img
                contain
                src="https://cdn.asriran.com/files/fa/news/1399/11/14/1181948_782.jpg"
                width="100%"
              ></v-img>
              <h4 class="mx-1">
                دیدنی های امروز؛ از کودتای میانمار تا چارلی چاپلین پاکستان
              </h4>
            </v-sheet>
            <v-img
              class="mt-3"
              src="https://mostatil.yektanet.com/media/300x100_resize.gif"
              width="100%"
              contain
            ></v-img>
            <v-sheet width="100%" outlined class="rounded mt-1">
              <v-sheet width="100%" height="30" outlined class="rounded-t">
                <div class="d-flex flex-row">
                  <v-btn
                    v-for="x in 5"
                    width="20%"
                    :key="x"
                    small
                    elevation="1"
                  >
                    ورزش</v-btn
                  >
                </div>
              </v-sheet>
            </v-sheet>
            <div class="d-flex flex-culomn justify-center">
              <v-sheet width="100%" elevation="1" class="pa-1 mb-1 rounded-b">
                <div v-for="x in 8" class="py-1" :key="x">
                  <h5>
                    <v-icon color="red">mdi-pan-bottom-left</v-icon>
                    مخالفت فراکسیون زنان با لغو مجازات زندان برای مهریه بیش از ۵
                    سکه/در طرح مجلس فقط مردها دیده شده‌اند
                  </h5>
                </div>
              </v-sheet>
            </div>
          </v-flex>
          <v-flex class="ma-1 justify-center" md2>
            <v-sheet class="pa-1">
              <v-row>
                <v-img
                  contain
                  class="my-2"
                  v-for="x in 10"
                  :key="x"
                  width="120"
                  height="200"
                  src="https://cdn.yektanet.com/assets/images/banner_branding/Asriran.jpg"
                >
                </v-img>
              </v-row>
            </v-sheet>
          </v-flex>
        </v-row>
      </v-sheet>
    </v-col>
  </v-row>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      items: ['web', 'shopping', 'videos', 'images', 'news'],
    }
  },
}
</script>
