<script setup>

import Vheader from "@/components/VHeader.vue";
import VFooter from "@/components/VFooter.vue";
import VPromo from "@/components/VPromo.vue";
import VProjects from "@/components/VProjects.vue";
import VTech from "@/components/VTech.vue";
import VFeedback from "@/components/VFeedback.vue";
</script>

<template>
  <vheader />
  <main>
    <v-promo />
    <v-projects />
    <v-tech />
    <v-feedback />
  </main>
  <v-footer></v-footer>
</template>

<style scoped>

</style>
