<template>
  <div>
    <v-row class="justify-center">
      <v-col sm="6">
        <div class="text-h6">BOWLER</div>
      </v-col>
    </v-row>
    <v-row class="justify-center">
      <v-col sm="8"><v-divider></v-divider></v-col>
    </v-row>
    <v-row class="justify-center">
      <v-col
        sm="6"
      >
      <v-btn
          class="mx-2"
          fab
          large
          outlined
        >
          0
        </v-btn>

        <v-btn
          class="mx-2"
          fab
          large
          outlined
        >
          1
        </v-btn>

        <v-btn
          class="mx-2"
          fab
          large
          outlined
        >
          2
        </v-btn>

        <v-btn
          class="mx-2"
          fab
          large
          outlined
        >
          3
        </v-btn>

        <v-btn
          class="mx-2"
          fab
          large
          outlined
        >
          4
        </v-btn>

        <v-btn
          class="mx-2"
          fab
          large
          outlined
        >
          5
        </v-btn>
        <v-btn
          class="mx-2"
          fab
          large
          outlined
        >
          6
        </v-btn>
      </v-col>
    </v-row>
    <v-row class="justify-center">
      <v-col
      sm="1"
      >
        <v-select
          :items="[0, 1, 2, 3, 4, 5, 6]"
          label="Extra"
        ></v-select>
      </v-col>
      <v-col
        sm="5"
      >
      <v-btn
          class="mx-2"
          fab
          large
          dark
          color="grey darken-3"
        >
          wide
        </v-btn>

        <v-btn
          class="mx-2"
          fab
          large
          dark
          color="grey darken-3"
        >
          no ball
        </v-btn>

        <v-btn
          class="mx-2"
          fab
          large
          dark
          color="grey darken-3"
        >
          bye
        </v-btn>

        <v-btn
          class="mx-2"
          fab
          large
          dark
          color="grey darken-3"
        >
          leg bye
        </v-btn>

        <v-btn
          class="mx-2"
          fab
          large
          dark
          color="error"
        >
        wicket
        </v-btn>

      </v-col>
    </v-row>
    <v-row class="justify-center">
      <v-col sm="8"><v-divider></v-divider></v-col>
    </v-row>
  </div>
</template>

<script>

  export default {
    name: 'HomeView',

  }
</script>
