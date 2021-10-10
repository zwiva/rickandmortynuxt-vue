<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card class="logo py-4 d-flex justify-center">
        <character-card :characters="characters" />
      </v-card>
    </v-col>
  </v-row>
</template>