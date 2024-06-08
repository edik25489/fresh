<script setup lang="ts">
const frame25 = ref(false)
</script>

<template>
  <v-card
      color="black"
  >
    <template v-slot:title>
      <p style="font-size: 80px; text-transform: uppercase; text-align: center; color: #d5880a;">Расписание</p>
    </template>
    <template v-slot:subtitle>
      <p style="text-align: center; text-transform: uppercase;">Актуально на 12.06.2024</p>
    </template>
  </v-card>
  <v-sheet
      class="bg-black d-flex flex-column justify-center align-center mx-auto"
  >
    <v-container>
      <v-table>
        <thead>
        <tr style="font-size: 30px;" class="bg-grey-lighten-2 text-[#d5880a]">
          <th class="text-center text-uppercase">
            пн
          </th>
          <th class="text-center text-uppercase">
            вт
          </th>
          <th class="text-center text-uppercase">
            ср
          </th>
          <th class="text-center text-uppercase">
            чт
          </th>
          <th class="text-center text-uppercase">
            пт
          </th>
          <th class="text-center text-uppercase">
            сб
          </th>
          <th class="text-center text-uppercase">
            вс
          </th>
        </tr>
        </thead>
        <tbody>
        <tr style="background: black;">
          <td></td> <td></td> <td></td> <td></td> <td></td> <td></td>
          <td class="text-center py-3">
            <p class="text-uppercase">фитнес</p>
            <p>большой зал</p>
            <p>13:00</p>
          </td>
        </tr>
        <tr style="background: black;">
          <td></td> <td></td> <td></td>
          <td class="text-center py-3">
            <p class="text-uppercase">3 +</p>
            <p>малый зал</p>
            <p>17:30</p>
          </td>
          <td class="text-center py-3">
            <p class="text-uppercase">гимнастика</p>
            <p>малый зал</p>
            <p>17:30</p>
          </td>
          <td></td>
          <td class="text-center py-3">
            <p class="text-uppercase">фитнес</p>
            <p>большой зал</p>
            <p>13:00</p>
          </td>
        </tr>
        <tr style="background: black;">
          <td class="text-center py-3">
            <p class="text-uppercase">3 +</p>
            <p>малый зал</p>
            <p>17:30</p>
          </td>
          <td class="text-center py-3">
            <p class="text-uppercase">гимнастика</p>
            <p>малый зал</p>
            <p>17:30</p>
          </td>
          <td></td> <td></td> <td></td> <td></td>
          <td class="text-center py-3">
            <p class="text-uppercase">фитнес</p>
            <p>большой зал</p>
            <p>13:00</p>
          </td>
        </tr>
        <tr style="background: black;">
          <td></td> <td></td>
          <td class="text-center py-3">
            <p class="text-uppercase">3 +</p>
            <p>малый зал</p>
            <p>17:30</p>
          </td>
          <td class="text-center py-3">
            <p class="text-uppercase">гимнастика</p>
            <p>малый зал</p>
            <p>17:30</p>
          </td>
          <td></td> <td></td>
          <td class="text-center py-3">
            <p class="text-uppercase">фитнес</p>
            <p>большой зал</p>
            <p>13:00</p>
          </td>
        </tr>
        <tr style="background: black;">
          <td class="text-center py-3">
            <p class="text-uppercase">фитнес</p>
            <p>большой зал</p>
            <p>13:00</p>
          </td>
          <td class="text-center py-3">
            <p class="text-uppercase">фитнес</p>
            <p>большой зал</p>
            <p>13:00</p>
          </td>
          <td class="text-center py-3">
            <p class="text-uppercase">фитнес</p>
            <p>большой зал</p>
            <p>13:00</p>
          </td>
          <td class="text-center py-3">
            <p class="text-uppercase">фитнес</p>
            <p>большой зал</p>
            <p>13:00</p>
          </td>
          <td class="text-center py-3">
            <p class="text-uppercase">фитнес</p>
            <p>большой зал</p>
            <p>13:00</p>
          </td>
          <td class="text-center py-3">
            <p class="text-uppercase">фитнес</p>
            <p>большой зал</p>
            <p>13:00</p>
          </td>
          <td></td>
        </tr>
        <tr style="background: black;">
          <td></td> <td></td> <td></td> <td></td> <td></td> <td></td>
          <td class="text-center py-3 px-1">
            <p class="text-uppercase">фитнес</p>
            <p>большой зал</p>
            <p>13:00</p>
          </td>
        </tr>
        </tbody>
      </v-table>
    </v-container>
  </v-sheet>

</template>

<style scoped>
table tr td{
  height: 80px; font-size: 18px; border: 4px white solid; color: #f69e0e;
}
td:hover{
  color: black;
  background: #f69e0e;
}
</style>