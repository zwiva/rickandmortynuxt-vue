<template>
  <v-card class="d-flex flex-wrap my-4 mx-4 px-4 py-4 text-left">
    <div v-for="(character, index) of characters" :key="index" class="text-right mx-auto px-3">
      <v-card-text class="headline">
        {{ character.name }}
      </v-card-text>
      <img class="VuetifyLogo" alt="Vuetify Logo" :src="character.image" />
    </div>
  </v-card>
</template>

<script>
export default {
  props: {
    characters: { type: Array, require: true },
  },
};
</script>

<style>
</style>