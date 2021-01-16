<template>
  <v-app-bar
    app
    color="light-blue darken-1"
    dense
    dark
  >

    <v-toolbar-title>
      <v-img
        src="@/assets/img/Instagram-Logo.png"
        
        max-width="110"
      >
        
      </v-img>
    </v-toolbar-title>
    <v-spacer />

    <v-btn icon
      to="/"
    >
      <v-icon>mdi-home-variant</v-icon>
    </v-btn>
    <v-btn icon>
      <v-icon>mdi-telegram</v-icon>
    </v-btn>
    <v-btn icon>
      <v-icon>mdi-compass</v-icon>
    </v-btn>
    <v-btn icon>
      <v-icon>mdi-heart-outline</v-icon>
    </v-btn>
    <v-btn icon
      to="/about"
    >
      <v-icon>mdi-account-circle</v-icon>
    </v-btn>
  </v-app-bar>
</template>

<script>
export default {
  name : 'CoreAppBar',

}
</script>

<style>

</style>