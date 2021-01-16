<template>
  <v-app>
    <core-app-bar />

    <v-main>
      <router-view />
    </v-main>
    <core-footer />
  </v-app>
</template>

<script>

import CoreAppBar from './components/core/AppBar'
import CoreFooter from './components/core/Footer.vue';
export default {
  name: 'App',

  components: {
    CoreAppBar,
    CoreFooter,

  },

  data: () => ({
    //
  }),
};
</script>
