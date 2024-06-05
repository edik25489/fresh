<script setup lang="ts">

</script>

<template>
<v-container class="my-16">
  <v-row>
    <v-col cols="12" class="my-6">
      <p style="font-size: 60px;" class="text-white text-center">СКОЛЬКО СТОИТ?</p>
    </v-col>
  </v-row>
  <v-row>
    <v-col cols="12" class="my-6">
      <v-sheet>
        <v-container class="d-flex flex-column px-16">
          <v-row style="font-size: 20px; border-bottom: 4px black solid" class="d-flex flex-row align-center justify-space-between pt-3">
            <div>ПРОБНОЕ</div>
            <div>300</div>
          </v-row>
          <v-row style="font-size: 20px; border-bottom: 4px black solid" class="d-flex flex-row align-center justify-space-between pt-3 mb-3">
            <div>АБОНЕМЕНТЫ</div>
            <div>от 1500</div>
          </v-row>
        </v-container>
      </v-sheet>
    </v-col>
  </v-row>
  <v-row>
    <v-col cols="12" class="d-flex flex-column align-center justify-center my-6">
      <v-btn
          class="px-7 ma-2"
          style="color: white;"
          rounded="md"
          color="#FF9F04"
          text="записаться на занятие"></v-btn>
      <p style="font-size: 14px; font-family: sans-serif;" class="font-italic text-white text-center">Напишите нам, чтобы узнать о специальном <br/>предложении для новых клиентов </p>
    </v-col>
  </v-row>
</v-container>
</template>

<style scoped>

</style>