<template>
  <v-col cols="12" class="d-flex flex-column justify-center">
    <p class="text-h3 text-white text-center font-weight-bold" width="100%">
      Experience
    </p>
    <v-row class="d-flex justify-center">
      <v-card max-width="1000" class="my-12 mx-2">
        <template v-slot:title>
        </template>
        <v-expansion-panels variant="popout" class=" mx-0 mt-2 mb-3 ">
          <WorkMako />
          <WorkFree />
          <WorkStrunobet />
          <WorkCerrad />
        </v-expansion-panels>
      </v-card>
    </v-row>
  </v-col>
</template>

<script setup >
import WorkMako from "./WorkMako.vue"
import WorkStrunobet from "./WorkStrunobet.vue"
import WorkCerrad from "./WorkCerrad.vue"
import WorkFree from "./WorkFree.vue"
</script>
