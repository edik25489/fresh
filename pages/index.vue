<script setup lang="ts">

</script>

<template>
  <v-container>
    <v-carousel
        height="752"
        cycle
        hide-delimiters
        class="mt-15"
    >
      <v-carousel-item
      >
        <v-sheet
        >
          <v-container fluid class="bg-black">
            <v-row>
              <v-col cols="7" class="position-static">
                <v-sheet class="bg-black position-absolute top-[10px] left-[40px] ml-auto font-italic font-weight-bold">
                  <p style="font-size: 170px; color: white; background: transparent;">ELEGANCE</p>
                  <p style="z-index: 10; font-size: 170px; color: white; background: transparent;">AND RHYTHM</p>
                </v-sheet>
              </v-col>
              <v-col cols="5" class="d-flex justify-center align-center">
                <v-img
                    width="470"
                    height="743"
                    src="@/assets/image 8.png"
                ></v-img>
              </v-col>
            </v-row>
          </v-container>
        </v-sheet>
      </v-carousel-item>

      <v-carousel-item
      >
        <v-sheet
            height="100%"
        >
          <div class="d-flex fill-height justify-center align-center bg-black">
            <div class="text-h2">
              Slide 2
            </div>
          </div>
        </v-sheet>
      </v-carousel-item>

      <v-carousel-item
      >
        <v-sheet
            height="100%"
        >
          <div class="d-flex fill-height justify-center align-center bg-black">
            <div class="text-h2">
              Slide 3
            </div>
          </div>
        </v-sheet>
      </v-carousel-item>
    </v-carousel>
  </v-container>

</template>

<style scoped>

</style>