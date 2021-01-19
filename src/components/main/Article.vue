<template>
  <div>
    <h1>MyNameIsArticle</h1>
    <UsernameBar />
    <Photo />
  </div>
</template>

<script>
import Photo from './Photo.vue'
import UsernameBar from "./UsernameBar.vue"

export default {
  name : 'Article',
  components: {
    UsernameBar,
    Photo
  }
}
    

</script>

<style>

</style>