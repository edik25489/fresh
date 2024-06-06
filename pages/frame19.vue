<script setup lang="ts">

</script>

<template>
  <v-card
      width="800"
      color="black"
      class="bg-black d-flex flex-column justify-center align-center mx-auto"
  >
    <template v-slot:title>
      <p style="font-size: 80px; text-align: center; color: #d5880a;">ФИТНЕС-ТАНЦЫ</p>
    </template>
    <template v-slot:subtitle>
      <p style="text-align: center; text-transform: uppercase;">сила. движение. интенсивность</p>
    </template>
    <template v-slot:text>
      <v-container>
        <v-row class="mb-5">
          <v-col cols="6" class="d-flex align-center justify-center">
            <p style="text-transform: uppercase; font-family: sans-serif; text-align: left;">
              фитнес-танцы - ЭТО КОМПЛЕКС СИЛОВЫХ ТРЕНИРОВОК, КОТОРЫЕ ПОМОГУТ ТЕБЕ ПРОКАЧАТЬ СВОЮ ВЫНОСЛИВОСТЬ И ПОВЫСИТЬ ТОНУС ВСЕГО ТЕЛА. ТЫ ПРОКАЧАЕШЬ МЫШЦЫ В ИНТЕНСИВНОМ РЕЖИМЕ И АТМОСФЕРЕ ДРАЙВА И СВОБОДЫ
            </p>
          </v-col>
          <v-col cols="6">
            <v-img cover src="@/assets/img/272.png"></v-img>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="6" class="d-flex flex-column justify-center">
            <p style="text-transform: uppercase; font-family: sans-serif; text-align: left;">
              тренер
            </p>
            <p style="font-size: 60px; font-family: sans-serif; text-transform: uppercase; text-align: center;">
              КАРОЛИНА
            </p>
            <p style="text-transform: uppercase; font-family: sans-serif; text-align: left;">
              динамичная нон-стоп тренировка, состоящая из танцевальных элементов и функциональных тренировочных упражнений, направленных на сжигание калорий и повышение тонуса тела            </p>
          </v-col>
          <v-col cols="6" class="d-flex align-center justify-center">
            <v-img style="height: 250px;" src="@/assets/img/25.png"></v-img>
          </v-col>
        </v-row>
      </v-container>
    </template>
  </v-card>
</template>

<style scoped>

</style>