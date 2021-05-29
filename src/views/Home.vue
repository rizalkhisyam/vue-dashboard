<template>
  <v-app :style="{ background: $vuetify.theme.themes.light.background }">
    <v-layout row>
      <v-flex md3>
        <v-app :style="{ background: $vuetify.theme.themes.light.background }">
          <v-container>
            <v-flex>
              <v-card class="ma-5 text-center mt-8" shaped elevation="10">
                <v-avatar class="mt-n6" size="60">
                  <img src="elon.jpg" alt="" />
                </v-avatar>
                <v-card-title class="layout justify-center">
                  Elon Musk
                </v-card-title>
                <v-card-subtitle class="layout justify-center">
                  49 year, South Africa
                </v-card-subtitle>
                <v-list class="mt-5">
                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Blood
                    </v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Height
                    </v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Weight
                    </v-list-item-title>
                  </v-list-item>
                  <v-list-item class="mt-5">
                    <v-list-item-subtitle>AB</v-list-item-subtitle>
                    <v-list-item-subtitle>170 cm</v-list-item-subtitle>
                    <v-list-item-subtitle>70 kg</v-list-item-subtitle>
                  </v-list-item>
                </v-list>
              </v-card>
            </v-flex>
            <v-flex>
              <v-card class="ma-5 mt-n2" shaped elevation="10">
                <v-list>
                  <v-list-item>
                    <v-list-item-avatar
                      class="cyan darken-1"
                      size="10"
                    ></v-list-item-avatar>
                    <v-list-item-title class="ml-n2"> Tesla </v-list-item-title>
                  </v-list-item>
                  <v-list-item class="text-center">
                    <v-list-item-title class="cyan--text text--darken-1"
                      >BTC</v-list-item-title
                    >
                    <v-list-item-title class="cyan--text text--darken-1"
                      >DOGE</v-list-item-title
                    >
                    <v-list-item-title class="cyan--text text--darken-1"
                      >ETH</v-list-item-title
                    >
                    <v-list-item-title class="cyan--text text--darken-1"
                      >XRP</v-list-item-title
                    >
                  </v-list-item>
                  <v-list-item class="mt-n5">
                    <v-list-item-subtitle
                      >Don't be afraid of new arenas</v-list-item-subtitle
                    >
                  </v-list-item>
                  <v-divider></v-divider>
                </v-list>

                <v-list two-line="" subheader="">
                  <v-list-item>
                    <v-list-item-avatar size="35">
                      <img src="elon.jpg" alt="" />
                    </v-list-item-avatar>
                    <v-list-item-content class="ml-n2">
                      <v-list-item-title
                        >Dr. Elon Musk To The Moon</v-list-item-title
                      >
                      <v-list-item-subtitle
                        >Tesla Hospital California</v-list-item-subtitle
                      >
                    </v-list-item-content>
                  </v-list-item>
                </v-list>

                <v-list two-line="" subheader="" class="mt-n5">
                  <v-list-item>
                    <v-list-item-title>Lorem ipsum</v-list-item-title>
                    <v-list-item-subtitle>Lorem ipsum</v-list-item-subtitle>
                  </v-list-item>
                </v-list>

                <v-list two-line="" subheader="" class="my-n4">
                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken-1"
                      >Date
                    </v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1"
                      >Time
                    </v-list-item-title>
                  </v-list-item>
                  <v-list-item class="mt-n10">
                    <v-list-item-title>27 Mei 2021 </v-list-item-title>
                    <v-list-item-title>15:00 pm </v-list-item-title>
                  </v-list-item>
                </v-list>
              </v-card>
            </v-flex>
            <v-flex>
              <v-card class="ma-5 text-center mt-6" shaped="" elevation="10">
                <v-list-item three-line="">
                  <v-list-item-content>
                    <v-list-item-title class="headline mb-1">
                      <v-icon>fab fa-cc-visa</v-icon>
                    </v-list-item-title>
                    <v-list-item-subtitle>
                      1234 0987 7890 2345
                    </v-list-item-subtitle>
                  </v-list-item-content>
                </v-list-item>
              </v-card>
            </v-flex>
          </v-container>
        </v-app>
      </v-flex>

      <v-flex md9>
        <v-app
          class="rounded"
          :style="{ background: $vuetify.theme.themes.dark.background }"
        >
          <v-container>
            <v-flex>
              <v-list class="mt-5">
                <v-list-item>
                  <v-list-item-title class="cyan--text text--darken-1"
                    >Some random text</v-list-item-title
                  >
                  <v-list-item-action>
                    <v-btn class="ma-2" tile outlined color="cyan darken-1">
                      <v-icon left>fas fa-eye</v-icon>See All
                    </v-btn>
                  </v-list-item-action>
                </v-list-item>
              </v-list>
            </v-flex>

            <v-flex>
              <v-row no-gutters>
                <v-col cols="12" md="4">
                  <v-row>
                    <v-col cols="12" md="2">
                      <v-card class="" height="80px" width="10px" color="green">
                      </v-card>
                    </v-col>
                    <v-col cols="12" md="10">
                      <v-list two-line="" subheader class="ml-n8">
                        <v-list-item>
                          <v-list-item-content>
                            <v-list-item-subtitle>
                              26 Mei, 2021
                            </v-list-item-subtitle>
                            <v-list-item-title>
                              Deleniti libero
                            </v-list-item-title>
                            <v-list-item-subtitle>
                              dolor sit amet
                            </v-list-item-subtitle>
                          </v-list-item-content>
                        </v-list-item>
                      </v-list>
                    </v-col>
                  </v-row>
                </v-col>

                <v-col cols="12" md="4">
                  <v-row>
                    <v-col cols="12" md="2">
                      <v-card class="" height="80px" width="10px" color="green">
                      </v-card>
                    </v-col>
                    <v-col cols="12" md="10">
                      <v-list two-line="" subheader class="ml-n8">
                        <v-list-item>
                          <v-list-item-content>
                            <v-list-item-subtitle>
                              26 Mei, 2021
                            </v-list-item-subtitle>
                            <v-list-item-title>
                              Deleniti libero
                            </v-list-item-title>
                            <v-list-item-subtitle>
                              dolor sit amet
                            </v-list-item-subtitle>
                          </v-list-item-content>
                        </v-list-item>
                      </v-list>
                    </v-col>
                  </v-row>
                </v-col>

                <v-col cols="12" md="4">
                  <v-row>
                    <v-col cols="12" md="2">
                      <v-card class="" height="80px" width="10px" color="green">
                      </v-card>
                    </v-col>
                    <v-col cols="12" md="10">
                      <v-list two-line="" subheader class="ml-n8">
                        <v-list-item>
                          <v-list-item-content>
                            <v-list-item-subtitle>
                              26 Mei, 2021
                            </v-list-item-subtitle>
                            <v-list-item-title>
                              Deleniti libero
                            </v-list-item-title>
                            <v-list-item-subtitle>
                              dolor sit amet
                            </v-list-item-subtitle>
                          </v-list-item-content>
                        </v-list-item>
                      </v-list>
                    </v-col>
                  </v-row>
                </v-col>
              </v-row>
            </v-flex>

            <v-col cols="12" md="4">
              <v-flex class="">
                <v-list>
                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Lorem ipsum is default text
                    </v-list-item-title>
                  </v-list-item>
                </v-list>

                <v-flex>
                  <v-row>
                    <v-date-picker color="" shaped elevation="10">
                    </v-date-picker>
                  </v-row>
                </v-flex>
              </v-flex>
            </v-col>
          </v-container>
        </v-app>
      </v-flex>
    </v-layout>
  </v-app>
</template>

<script>
export default {
  data: () => ({}),

  computed: {
    theme() {
      return this.$vuetify.theme.dark ? "dark" : "light";
    },
  },

  methods: {},
};
</script>
