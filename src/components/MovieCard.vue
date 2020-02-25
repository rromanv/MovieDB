<template>
  <v-card>
    <v-img class="white--text align-end" height="200px" src="https://cdn.vuetifyjs.com/images/cards/docks.jpg" />
    <v-card-title>Movie Name</v-card-title>
    <v-card-subtitle class="pb-0">
      <v-chip v-for="n in 3" :key="n" class="ma-2 purple--text text--darken-4" color="purple lighten-4" x-small>
        Genre
      </v-chip>
    </v-card-subtitle>

    <v-card-text class="text--primary">
      Movie Description or Overview
    </v-card-text>

    <v-card-actions>
      <v-btn color="purple" text>
        Love it
      </v-btn>
      <v-spacer />
      <v-btn color="orange" text>
        Watchlist
      </v-btn>
    </v-card-actions>
  </v-card>
</template>

<script>
export default {
  name: 'MovieCard',
}
</script>
