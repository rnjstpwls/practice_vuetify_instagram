<template>
  <v-card
    class="mx-3"
    tile
    max-height="200"
  >
    <v-carousel 
      :show-arrows="false"
      hide-delimiter-background
      hide-delimiters
    >
      <v-carousel-item
        v-for="(item, idx) in items"
        :key="idx"
        :src="item.src"
        max-height="200"
      ></v-carousel-item>
    </v-carousel>
  </v-card>
</template>

<script>
  export default {
    name: 'Photo',
    data () {
      return {
        items: [
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
          },
        ],
      }
    },
  }
</script>

<style>

</style>