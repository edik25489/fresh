<script setup lang="ts">

</script>

<template>
  <v-card
      width="800"
      color="black"
      class="bg-black d-flex flex-column justify-center align-center mx-auto"
  >
    <template v-slot:title>
      <p style="font-size: 80px; text-align: center; color: #d5880a; text-transform: uppercase;">брейкданс</p>
    </template>
    <template v-slot:subtitle>
      <p style="text-align: center; text-transform: uppercase;">свобода. стиль. движение</p>
    </template>
    <template v-slot:text>
      <v-container>
        <v-row class="mb-5">
          <v-col cols="6" class="d-flex align-center justify-center">
            <p style="text-transform: uppercase; font-family: sans-serif; text-align: left;">
              Брейк - НАПРАВЛЕНИЕ ПРО ТОТАЛЬНУЮ СВОБОДУ, ДЕРЗКИЕ, ЭКСПРЕССИВНЫЕ ДВИЖЕНИЯ. РИТМИЧНО, ДВИЖОВО, С «УЛИЧНЫМ» НАСТРОЕНИЕМ.
            </p>
          </v-col>
          <v-col cols="6">
            <v-img cover src="@/assets/img/86.png"></v-img>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="6" class="d-flex flex-column justify-center">
            <p style="text-transform: uppercase; font-family: sans-serif; text-align: left;">
              тренер
            </p>
            <p style="font-size: 60px; font-family: sans-serif; text-transform: uppercase; text-align: center;">
              денис
            </p>
            <p style="text-transform: uppercase; font-family: sans-serif; text-align: left;">
              на занятиях  Денисом всегда жарко — все хореографии уникальные, динамичные, заряженные положительной энергией тренера
            </p>
          </v-col>
          <v-col cols="6" class="d-flex align-center justify-center">
            <v-img style="height: 250px;" src="@/assets/img/216.png"></v-img>
          </v-col>
        </v-row>
      </v-container>
    </template>
  </v-card>
</template>

<style scoped>

</style>