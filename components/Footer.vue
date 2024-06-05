<script setup lang="ts">

</script>

<template>
<v-container class="position-relative" style="height: 300px;">
  <v-row>
    <v-sheet class="mx-auto d-flex align-center justify-center my-6 bg-transparent">
      <p style="font-size: 50px; color: #FEFDFD;">РАСТЕМ ВМЕСТЕ С ВАМИ!</p>
    </v-sheet>
  </v-row>
  <v-row>
    <v-sheet class="my-6 bg-transparent">
        <v-img
            :width="100"
            aspect-ratio="16/9"
            cover
            src="@/assets/logo.svg"
            class="position-absolute"
            style="position: absolute; bottom: 0; left: 0;"
        ></v-img>

      <div class="position-absolute d-flex flex-column align-end justify-end" style="bottom: 0; right: 0;">
        <p style="font-size: 40px; color: #d5880a;">СЛЕДИТЕ ЗА НОВОСТЯМИ</p>
        <div>
          <v-icon color="white" size="40" icon="mdi-instagram"></v-icon>
          <v-icon color="white" size="40" icon="mdi-account-circle"></v-icon>
        </div>
      </div>
    </v-sheet>
  </v-row>
</v-container>
</template>

<style scoped>

</style>