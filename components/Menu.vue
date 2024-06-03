<script setup lang="ts">

</script>

<template>

    <v-app-bar
        color="#000"
        flat
    >
      <template v-slot:prepend>
        <v-img
            :width="100"
            aspect-ratio="16/9"
            cover
            src="@/assets/logo.svg"
        ></v-img>
      </template>

      <template v-slot:default>
        <v-spacer></v-spacer>
        <v-btn>РАСПИСАНИЕ</v-btn>
        <v-btn>СОБЫТИЯ</v-btn>
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