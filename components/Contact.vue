<script setup lang="ts">
const dialog = ref(false)
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
            @click="dialog = true"
            color="#FF9F04"
            text="записаться на занятие"></v-btn>
      </v-sheet>
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