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
        <NuxtLink>
          <v-hover  v-slot="{ isHovering, props }" close-delay="100">
            <v-sheet
                v-bind="props"
                :class="{ 'on-hover': isHovering, 'text-black': isHovering, 'text-white': !isHovering }"
                :color="isHovering ? 'orange-darken-2' : 'black'"
                class="d-flex align-center justify-center my-5"
                style="background-color: transparent; border: 2px white solid; height: 200px; font-size: 50px;">
              СТРЕТЧИНГ
            </v-sheet>
          </v-hover>
        </NuxtLink>

        <NuxtLink>
          <v-hover  v-slot="{ isHovering, props }" close-delay="100">
          <v-sheet
              v-bind="props"
              :class="{ 'on-hover': isHovering, 'text-black': isHovering, 'text-white': !isHovering }"
              :color="isHovering ? 'orange-darken-2' : 'black'"
              class="d-flex align-center justify-center my-5"
              style="background-color: transparent; border: 2px white solid; height: 200px; color: white; font-size: 30px;">
            ФИТНЕС-ТАНЦЫ
          </v-sheet>
          </v-hover>
        </NuxtLink>
      </v-col>
      <v-col cols="4">
        <NuxtLink>
          <v-hover  v-slot="{ isHovering, props }" close-delay="100">
          <v-sheet
              v-bind="props"
              :class="{ 'on-hover': isHovering, 'text-black': isHovering, 'text-white': !isHovering }"
              :color="isHovering ? 'orange-darken-2' : 'black'"
              class="d-flex align-center justify-center ma-5"
              style="background-color: transparent; border: 2px white solid; height: 250px; color: white; font-size: 50px;">
            16+
          </v-sheet>
          </v-hover>
        </NuxtLink>
        <NuxtLink>
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
        </NuxtLink>
      </v-col>
      <v-col cols="4">
        <NuxtLink>
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
        </NuxtLink>
        <v-row>

          <v-col cols="6">
            <NuxtLink>
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
            </NuxtLink>
          </v-col>
          <v-col cols="6">
            <NuxtLink>
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
            </NuxtLink>
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