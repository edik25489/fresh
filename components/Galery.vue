<script setup lang="ts">

</script>

<template>
<v-container class="mb-16 position-relative" id="gallery">
  <v-row>
    <v-img cover height="300px" src="@/assets/img/image 19.png"></v-img>
    <v-img cover height="300px" src="@/assets/img/image 20.png"></v-img>
    <v-img cover height="300px" src="@/assets/img/image 24.png"></v-img>
    <v-img cover height="300px" src="@/assets/img/image 23.png"></v-img>
  </v-row>
  <v-row>
    <v-img cover height="300px" style="width: 200px;" src="@/assets/img/image 21.png"></v-img>
    <v-img cover height="300px" src="@/assets/img/image 22.png"></v-img>
    <v-img cover height="300px" src="@/assets/img/image 6.png"></v-img>
    <v-img cover height="300px" src="@/assets/img/image 18.png"></v-img>
  </v-row>
  <v-sheet
      class="position-absolute bg-black"
      width="500px"
      height="150px"
      style="top: 45%; left: 40%;">
    <p style="font-size: 30px; color: #d5880a; margin-left: 10px;">EVENTS</p>
    <p style="position: absolute;  font-size: 14px; text-transform: uppercase; bottom: 0; text-align: right;">Мастер-классы, открытые тренировки, концерты, конкурсы, фестивали, всероссийские чемпионаты.  FResh создаёт трамплин для развития учеников</p>
  </v-sheet>
</v-container>
</template>

<style scoped>

</style>