<script setup lang="ts">

</script>

<template>

<v-container>
  <v-sheet
      style="font-size: 50px;"
      class="bg-black text-orange-darken-2 mt-10 mb-4">
    ГРУППЫ
  </v-sheet>
  <v-sheet class="bg-black">
    <v-row no-gutters>
      <v-col cols="4">

          <v-hover  v-slot="{ isHovering, props }" close-delay="100">
            <v-sheet
                v-bind="props"
                :class="{ 'on-hover': isHovering, 'text-black': isHovering, 'text-white': !isHovering }"
                :color="isHovering ? 'orange-darken-2' : 'black'"
                class="d-flex align-center justify-center my-5"
                style="background-color: transparent; border: 2px white solid; height: 200px;">
              <v-btn
                  variant="text"
                  style="height: 200px; font-size: 50px;"
                  to="/frame18"
              > СТРЕТЧИНГ</v-btn>

            </v-sheet>
          </v-hover>


          <v-hover  v-slot="{ isHovering, props }" close-delay="100">
          <v-sheet
              v-bind="props"
              :class="{ 'on-hover': isHovering, 'text-black': isHovering, 'text-white': !isHovering }"
              :color="isHovering ? 'orange-darken-2' : 'black'"
              class="d-flex align-center justify-center my-5"
              style="background-color: transparent; border: 2px white solid; height: 200px;">
            <v-btn
                variant="text"
                style="height: 200px; font-size: 30px;"
                to="/frame19"
            > ФИТНЕС-ТАНЦЫ</v-btn>
          </v-sheet>
          </v-hover>
      </v-col>
      <v-col cols="4">

          <v-hover  v-slot="{ isHovering, props }" close-delay="100">
          <v-sheet
              v-bind="props"
              :class="{ 'on-hover': isHovering, 'text-black': isHovering, 'text-white': !isHovering }"
              :color="isHovering ? 'orange-darken-2' : 'black'"
              class="d-flex align-center justify-center ma-5"
              style="background-color: transparent; border: 2px white solid; height: 250px;">
            <v-btn
                variant="text"
                style="height: 250px; font-size: 50px;"
                to="/FRAME20"
            >16+</v-btn>
          </v-sheet>
          </v-hover>


          <v-hover  v-slot="{ isHovering, props }" close-delay="100">
          <v-sheet
              v-bind="props"
              :class="{ 'on-hover': isHovering, 'text-black': isHovering, 'text-white': !isHovering }"
              :color="isHovering ? 'orange-darken-2' : 'black'"
              class="d-flex align-center justify-center ma-5"
              style="background-color: transparent; border: 2px white solid; height: 150px; color: white; font-size: 30px;">
            ЛАТИНА
          </v-sheet>
          </v-hover>

      </v-col>
      <v-col cols="4">

          <v-hover  v-slot="{ isHovering, props }" close-delay="100">
          <v-sheet
              v-bind="props"
              :class="{ 'on-hover': isHovering, 'text-black': isHovering, 'text-white': !isHovering }"
              :color="isHovering ? 'orange-darken-2' : 'black'"
              class="d-flex align-center justify-center my-5"
              style="background-color: transparent; border: 2px white solid; height: 100px; color: white; font-size: 50px;">
            БРЕЙК
          </v-sheet>
          </v-hover>

        <v-row>

          <v-col cols="6">

            <v-hover  v-slot="{ isHovering, props }" close-delay="100">
              <v-sheet
                  v-bind="props"
                  :class="{ 'on-hover': isHovering, 'text-black': isHovering, 'text-white': !isHovering }"
                  :color="isHovering ? 'orange-darken-2' : 'black'"
                  class="d-flex align-center justify-center"
                  style="background-color: transparent; border: 2px white solid; height: 300px; color: white; font-size: 50px;">
                3+
              </v-sheet>
            </v-hover>

          </v-col>
          <v-col cols="6">

              <v-hover  v-slot="{ isHovering, props }" close-delay="100">
                <v-sheet
                    v-bind="props"
                    :class="{ 'on-hover': isHovering, 'text-black': isHovering, 'text-white': !isHovering }"
                    :color="isHovering ? 'orange-darken-2' : 'black'"
                    class="d-flex align-center justify-center"
                    style="background-color: transparent; border: 2px white solid; height: 300px; color: white; font-size: 50px;">
                  6+
                </v-sheet>
              </v-hover>

          </v-col>
        </v-row>

      </v-col>
    </v-row>
  </v-sheet>
</v-container>
</template>

<style scoped>
.my-hover:hover{
  color: black;
  background-color: #d5880a;
}
</style>