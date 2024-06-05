<script setup lang="ts">

</script>

<template>
<v-container class="my-6 bg-white" style="height: 600px;">
  <v-row class="d-flex flex-row justify-center align-center">
    <v-col>
      <v-sheet style="height: 400px;" class="d-flex flex-column align-center justify-center">
        <p style="line-height: 50px; font-size: 50px; color: #d5880a;" class="text-center">ПРОЯВИТЕ <br/>СЕБЯ С НАМИ!</p>
        <p
            style="font-size: 14px; line-height: 20px; font-style: italic;"
            class="text-center">
          Вы можете привести своего ребёнка на пробное занятие, и <br/>понаблюдать, на сколько ему будет комфортно.
          <span style="font-weight: bold">
            Уверены, <br/>что connect с педагогом вы почувствуете сразу же!
          </span>
        </p>
      </v-sheet>
    </v-col>

    <v-col>
      <v-sheet
          style="height: 200px; width: 400px;"
          class="d-flex flex-column align-center justify-space-around bg-black pa-5">
        <p
            style="font-size: 24px; line-height: 30px;"
            class="text-center">
          Стоимость пробного занятия - 300 рублей
        </p>
        <v-btn
            class="px-7 ma-2"
            style="color: white;"
            rounded="md"
            color="#FF9F04"
            text="записаться на занятие"></v-btn>
      </v-sheet>
    </v-col>
  </v-row>
</v-container>
</template>

<style scoped>

</style>