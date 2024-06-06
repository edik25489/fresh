<script setup lang="ts">
const dialog = ref(false)
</script>

<template>
  <v-container>
    <v-sheet
        style="font-size: 50px;"
        class="bg-transparent text-white mt-10 mb-4">
      FRESH IS ABOUT
    </v-sheet>
    <v-sheet
        class="mx-auto bg-black"
    >
      <v-slide-group
          class="pa-4"
          show-arrows
      >
        <v-slide-group-item
        >
          <v-card
              class="ma-4"
              height="420"
              width="300"
          >
            <div
                style="background-position: center; background-size: cover; background-image: url(/about/70.png); background-repeat: no-repeat;"
                class="d-flex fill-height flex-column align-center justify-center px-4">
              <div style="font-size: 100px; line-height: 40px; font-weight: bold; color: #FEFDFD;">2</div>
              <div style="font-size: 30px; line-height: 80px; font-weight: bold; color: #FEFDFD;">СТУДИИ</div>
              <div class="text-center" style="font-size: 16px; line-height: 20px; font-weight: bold; color: #FEFDFD;">ДОБРАТЬСЯ ДО НАС ПРОЩЕ ПРОСТОГО</div>
            </div>
          </v-card>
          <v-card
              class="ma-4"
              height="420"
              width="300"
          >
            <div
                style="background-position: center; background-size: cover; background-image: url(/about/ed.png); background-repeat: no-repeat;"
                class="d-flex fill-height flex-column align-center justify-center px-4">
              <div style="font-size: 100px; line-height: 40px; font-weight: bold; color: #FEFDFD;">10+</div>
              <div style="font-size: 30px; line-height: 80px; font-weight: bold; color: #FEFDFD;">ПЕДАГОГОВ</div>
              <div class="text-center" style="font-size: 16px; line-height: 20px; font-weight: bold; color: #FEFDFD;">АВТОРСКИЙ СТИЛЬ И СВОЙ VIBE У КАЖДОГО</div>
            </div>
          </v-card>
          <v-card
              class="ma-4"
              height="420"
              width="300"
          >
            <div
                style="background-position: center; background-size: cover; background-image: url(/about/18.png); background-repeat: no-repeat;"
                class="d-flex fill-height flex-column align-center justify-center px-4">
              <div style="font-size: 80px; line-height: 40px; font-weight: bold; color: #FEFDFD;">650+</div>
              <div style="font-size: 30px; line-height: 80px; font-weight: bold; color: #FEFDFD;">УЧЕНИКОВ</div>
              <div class="text-center" style="font-size: 16px; line-height: 20px; font-weight: bold; color: #FEFDFD;">С 3 ЛЕТ <br/> ПОМОГАЕМ КАЖДОМУ РЕБЕНКУ РАСКРЫТЬСЯ НА СЦЕНЕ</div>
            </div>
          </v-card>
          <v-card
              class="ma-4"
              height="420"
              width="300"
          >
            <div
                style="background-position: center; background-size: cover; background-image: url(/about/b9.png); background-repeat: no-repeat;"
                class="d-flex fill-height flex-column align-center justify-center px-4">
              <div style="font-size: 40px; line-height: 40px; font-weight: bold; color: #FEFDFD;">ФИТНЕС-ТАНЦЫ</div>
              <div style="font-size: 40px; line-height: 40px; font-weight: bold; color: #FEFDFD;">СТРЕТЧИНГ</div>
              <div class="text-center" style="font-size: 16px; line-height: 20px; font-weight: bold; color: #FEFDFD;">ЗАНИМАЕМСЯ ВСЕЙ СЕМЬЕЙ! ПОМОГАЕМ ВАМ СТАНОВИТЬСЯ ЛУЧШЕ!</div>
            </div>
          </v-card>
          <v-card
              class="ma-4"
              height="420"
              width="300"
          >
            <div
                style="background-position: center; background-size: cover; background-image: url(/about/0e.png); background-repeat: no-repeat;"
                class="d-flex fill-height flex-column align-center justify-center px-4">
              <div class="text-center" style="font-size: 40px; line-height: 40px; font-weight: bold; color: #FEFDFD;">ЖДЕМ ВАС НА ЗАНЯТИЯХ</div>
              <v-btn
                  rounded="md"
                  color="#FF9F04"
                  @click="dialog = true"
                  text="записаться на занятие"></v-btn>
            </div>
          </v-card>
        </v-slide-group-item>
      </v-slide-group>
    </v-sheet>
  </v-container>
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
</template>

<style scoped>

</style>