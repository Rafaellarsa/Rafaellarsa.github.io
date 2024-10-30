<template>
  <v-app-bar>
    <v-app-bar-title color="deep-purple-accent-4"
      ><span class="text-primary">Rafaella Sampaio</span></v-app-bar-title
    >

    <!-- <v-tabs v-model="tab" align-tabs="end" color="deep-purple-accent-4">
      <v-tab :value="1">Landscape</v-tab>
      <v-tab :value="2">City</v-tab>
      <v-tab :value="3">Abstract</v-tab>
    </v-tabs> -->
    <v-switch
      v-model="darkMode"
      color="primary"
      label="Dark Mode"
      hide-details
      class="mr-4"
    />
  </v-app-bar>
</template>

<script setup>
import { ref, watch } from "vue";
import { useTheme } from "vuetify";

const theme = useTheme();
const tab = ref(null);
const darkMode = ref(false);

watch(darkMode, async (newValue) => {
  theme.global.name.value = newValue ? "dark" : "light";
});
</script>
