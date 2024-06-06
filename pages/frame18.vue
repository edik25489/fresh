<script setup lang="ts">
const frame18 = ref(false)
</script>

<template>
    <v-card
        width="800"
        color="black"
        class="bg-black d-flex flex-column justify-center align-center mx-auto"
    >
      <template v-slot:title>
        <p style="font-size: 80px; text-align: center; color: #d5880a;">СТРЕТЧИНГ</p>
      </template>
      <template v-slot:subtitle>
        <p style="text-align: center; text-transform: uppercase;">гибкость. растяжка. глубина</p>
      </template>
      <template v-slot:text>
        <v-container>
          <v-row class="mb-5">
            <v-col cols="6" class="d-flex align-center justify-center">
              <p style="text-transform: uppercase; font-family: sans-serif; text-align: left;">
                STRETCHINg— ЭТО ТРЕНИРОВКА С ФОКУСОМ НА РАСТЯЖКУ И ПРОРАБОТКУ ГИБКОСТИ ВСЕХ МЫШЦ ТЕЛА. СПЕЦИАЛИЗИРОВАННЫЕ РАЗОГРЕВАЮЩИЕ УПРАЖНЕНИЯ ДЛЯ ТОГО, ЧТОбы ПОВЫСИТЬ ТОНУС ТЕЛА И УКРЕПИТЬ ЗДОРОВЬЕ.
              </p>
            </v-col>
            <v-col cols="6">
              <v-img cover src="@/assets/img/27.png"></v-img>
            </v-col>
          </v-row>
          <v-row>
            <v-col cols="6" class="d-flex flex-column justify-center">
              <p style="text-transform: uppercase; font-family: sans-serif; text-align: left;">
                тренер
              </p>
              <p style="font-size: 70px; font-family: sans-serif; text-transform: uppercase; text-align: center;">
                МАРИНА
              </p>
              <p style="text-transform: uppercase; font-family: sans-serif; text-align: left;">
                тренировка по стретчингу с Мариной - это занятие на улучшение качества движения, цель которого - не перегрузить отдельную мышцу/часть тела, а комплексно проработать тело - целостно и равномерно
              </p>
            </v-col>
            <v-col cols="6" class="d-flex align-center justify-center">
              <v-img style="height: 250px;" src="@/assets/img/81.png"></v-img>
            </v-col>
          </v-row>
        </v-container>
      </template>
    </v-card>
</template>

<style scoped>

</style>