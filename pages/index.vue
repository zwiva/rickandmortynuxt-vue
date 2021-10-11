<template>
  <v-row justify="center" align="center" class="justify-content-center mx-auto">
    <character-card :characters="characters" />
  </v-row>
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