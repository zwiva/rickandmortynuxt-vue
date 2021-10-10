<template>
  <v-card>
    <div v-for="(character, index) of characters" :key="index">
      <v-card-title class="headline">
        {{ character.name }}
      </v-card-title>
      <img class="VuetifyLogo" alt="Vuetify Logo" :src="character.image" />
    </div>
  </v-card>
</template>

<script>
export default {
  data() {
    return {
      characters: [
        {
          id: 1,
          name: "Morty",
          image: "https://rickandmortyapi.com/api/character/avatar/2.jpeg",
        },
        {
          id: 2,
          name: "Rick",
          image: "https://rickandmortyapi.com/api/character/avatar/1.jpeg",
        },
        {
          id: 3,
          name: "Summer",
          image: "https://rickandmortyapi.com/api/character/avatar/3.jpeg",
        },
        {
          id: 4,
          name: "Beth",
          image: "https://rickandmortyapi.com/api/character/avatar/4.jpeg",
        },
        {
          id: 5,
          name: "Jerry",
          image: "https://rickandmortyapi.com/api/character/avatar/5.jpeg",
        },
      ],
    };
  },
};
</script>

<style>
</style>