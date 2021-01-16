<template>
  <v-app>
    <core-app-bar />

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>

import CoreAppBar from './components/core/AppBar'
export default {
  name: 'App',

  components: {
    CoreAppBar,
  },

  data: () => ({
    //
  }),
};
</script>
