<script setup lang="ts">

import Menu from "~/components/Menu.vue";
import Footer from "~/components/Footer.vue";
</script>

<template>
<v-app
    style="background: black;"
>
    <Menu/>
  <v-main>
    <slot/>
  </v-main>
    <Footer/>
</v-app>
</template>

<style scoped>

</style>