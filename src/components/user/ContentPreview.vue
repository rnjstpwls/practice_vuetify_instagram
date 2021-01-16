<template>
  <v-row no-gutters>
    <v-col
      v-for="(content, idx) in contents" :key="idx"
      
      class="d-flex child-flex pa-1"
      cols="4"
    >
      <ContentImage :content="content" />
    </v-col>
  </v-row>
</template>

<script>
import ContentImage from './ContentImage.vue'
export default {
  name : 'ContentPreview',
  components: {
    ContentImage,

  },
  data: () => ({
    contents: [1, 2, 3, 4, 5, 6, 7, 8, 9]
  })
}
</script>

<style>

</style>