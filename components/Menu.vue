<script setup lang="ts">

</script>

<template>

    <v-app-bar
        color="#000"
        flat
    >
      <template v-slot:prepend>
        <v-btn to="/">
          <v-img
              :width="100"
              aspect-ratio="16/9"
              cover
              src="@/assets/logo.svg"
          ></v-img>
        </v-btn>

      </template>

      <template v-slot:default>
        <v-spacer></v-spacer>
        <v-btn href="/frame25">РАСПИСАНИЕ</v-btn>
        <v-btn href="#gallery">СОБЫТИЯ</v-btn>
        <v-spacer></v-spacer>
        <v-spacer></v-spacer>
      </template>

      <template v-slot:append>
        <v-btn>INST</v-btn>
      </template>
    </v-app-bar>

</template>

<style scoped>

</style>