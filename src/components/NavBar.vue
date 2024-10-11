<template>
  <v-app-bar>
    <v-app-bar-title>Rafaella Sampaio</v-app-bar-title>

    <!-- <v-tabs v-model="tab" align-tabs="end" color="deep-purple-accent-4">
      <v-tab :value="1">Landscape</v-tab>
      <v-tab :value="2">City</v-tab>
      <v-tab :value="3">Abstract</v-tab>
    </v-tabs> -->
    <v-switch
      v-model="darkMode"
      color="deep-purple-accent-4"
      label="Dark Mode"
      value="deep-purple-accent-4"
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
