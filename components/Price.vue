<script setup lang="ts">
const dialog = ref(false)
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
          @click="dialog = true"
          text="записаться на занятие"></v-btn>
      <p style="font-size: 14px; font-family: sans-serif;" class="font-italic text-white text-center">Напишите нам, чтобы узнать о специальном <br/>предложении для новых клиентов </p>
    </v-col>
  </v-row>
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