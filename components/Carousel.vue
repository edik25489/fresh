<script setup lang="ts">
const dialog = ref(false)
</script>

<template>
  <v-container>
    <v-carousel
        height="500"
        cycle
        hide-delimiters
        class="mt-15"
    >
      <v-carousel-item
      >
        <v-sheet
        >
          <v-container fluid class="bg-black">
            <v-row>
              <v-col cols="7" class="position-static">
                <v-sheet class="bg-black position-absolute top-[10px] left-[40px] ml-auto font-italic font-weight-bold">
                  <p style="line-height: 70px; font-size: 100px; color: white; background: transparent;">ELEGANCE</p>
                  <p style="text-indent: 70px; font-size: 100px; color: white; background: transparent; position: relative;">
                    <img src="@/assets/Star.svg" alt="" style="height: 60px; position: absolute; top: 60px; left: 40px;">
                    <img src="@/assets/Star.svg" alt="" style="height: 60px; position: absolute; top: 20px; left: 65px;">
                    AND RHYTHM
                  </p>
                  <v-sheet
                      width="400"
                      class="position-absolute bg-black"
                  >
                    <p style="font-style: italic; font-family: sans-serif; line-height: 30px; position: absolute; left: 70px; top: 80px;">
                      Найдите для себя время. <br/>
                      Потанцуйте. Это так оживляет, <br/>
                      вдохновляет и захватывает! <br/>
                      Когда ты танцуешь — ты живёшь!</p>
                    <v-btn
                        style="top: 220px; left: 70px;"
                        rounded="md"
                        color="#FF9F04"
                        position="absolute"
                        @click="dialog = true"
                        text="записаться на занятие"></v-btn>
                    <img src="@/assets/Star.svg" alt="" style="height: 60px; position: absolute; top: 190px; left: 370px;">
                    <img src="@/assets/Star.svg" alt="" style="height: 60px; position: absolute; top: 210px; left: 330px;">

                  </v-sheet>

                </v-sheet>
              </v-col>
              <v-col cols="5" class="position-static">
                <v-img
                    height="470"
                    style="bottom: 0; right: 0;"
                    src="@/assets/image 8.png"
                ></v-img>
              </v-col>
            </v-row>
          </v-container>
        </v-sheet>
      </v-carousel-item>
      <v-carousel-item
      >
        <v-sheet
        >
          <v-container fluid class="bg-black">
            <v-row>
              <v-col cols="12" class="position-static">
                <v-sheet class="bg-black position-absolute top-[10px] left-[40px] ml-auto font-italic font-weight-bold">
                  <p style="text-indent: 70px; line-height: 110px; font-size: 100px; color: white; background: transparent;">WELCOME</p>
                  <p style="text-indent: 70px; line-height: 110px; font-size: 100px; color: white; background: transparent;">TO <span style="color: #d5880a;">FRESH</span></p>
                  <v-sheet
                      width="400"
                      class="position-absolute bg-black"
                  >
                    <p style="font-style: italic; font-family: sans-serif; line-height: 30px; position: absolute; left: 70px; top: 100px;">
                      Студия современных танцев для <br/>
                      детей и взрослых. С нами твое <br/>
                      сердце будет биться чаще</p>
                    <v-btn
                        style="top: 200px; left: 70px;"
                        rounded="md"
                        color="#FF9F04"
                        position="absolute"
                        @click="dialog = true"
                        text="записаться на занятие"></v-btn>
                  </v-sheet>

                </v-sheet>
              </v-col>
              <v-col cols="5" class="position-static">
                <img src="@/assets/Star.svg" alt="" style="height: 60px; position: absolute; top: 200px; right: 190px;">
                <img src="@/assets/Star.svg" alt="" style="height: 40px; position: absolute; top: 160px; right: 225px;">
                <v-img
                    style="position:absolute; bottom: 0; right: 0;"
                    width="470"
                    src="@/assets/image7.svg"
                ></v-img>
              </v-col>
            </v-row>
          </v-container>
        </v-sheet>
      </v-carousel-item>
      <v-carousel-item
      >
        <v-sheet
        >
          <v-container fluid class="bg-black">
            <v-row class="position-static">

              <v-sheet class="bg-transparent position-absolute top-[10px] left-[40px] ml-auto font-weight-bold">
                <p style="font-size: 90px; color: white;">
                  LET'S KEEP
                </p>
              </v-sheet>


              <v-img
                  class="position-absolute top-0"
                  style="left: 150px;"
                  width="688"
                  height="562"
                  src="@/assets/002A4534.svg"
              ></v-img>

              <v-sheet
                  width="400"
                  class="position-absolute bg-transparent"
                  style="left: 0; bottom: 0;"
              >
                <p style="font-style: italic; font-family: sans-serif; line-height: 30px;">
                  Умение танцевать дает тебе величайшую <br/>
                  из свобод: выразить всего себя в полной<br/>
                  мере таким, какой ты есть</p>
              </v-sheet>
              <v-sheet
                  style="top: 200px; right: 90px;"
                  class="bg-transparent position-absolute font-weight-bold">
                <p style="font-size: 90px; color: white;">
                  ON DANCING
                </p>
              </v-sheet>
              <v-btn
                  style="bottom: 5px; right: 0;"
                  rounded="md"
                  color="#FF9F04"
                  position="absolute"
                  @click="dialog = true"
                  text="записаться на занятие"></v-btn>
            </v-row>
          </v-container>
        </v-sheet>
      </v-carousel-item>
    </v-carousel>

    <v-dialog
        v-model="dialog"
        width="auto"
        class="bg-black"
    >
      <v-card
          width="600"
          color="black"
          class="bg-black"
      >
        <template v-slot:title>
          <p style="font-size: 50px;">ХОЧУ ВО FRESH</p>
        </template>
        <template v-slot:text>
          <v-text-field
              label="ФИО РОДИТЕЛЯ"
              required
          ></v-text-field>
          <v-text-field
              label="ФИО РЕБЕНКА"
              required
          ></v-text-field>
          <v-text-field
              label="НОМЕР ТЕЛЕФОНА"
              required
          ></v-text-field>
        </template>
        <template v-slot:actions>
          <v-btn
              class="px-14"
              text="оставить заявку"
              color="#FF9F04"
              variant="flat"
              @click="dialog = false"
          >
            <span style="color: #FEFDFD">оставить заявку</span>
          </v-btn>
        </template>
      </v-card>
    </v-dialog>

  </v-container>

</template>

<style scoped>

</style>