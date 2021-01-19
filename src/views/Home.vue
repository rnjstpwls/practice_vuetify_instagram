<template>
  <div class="home">
    <Article />
    <Article />
  </div>
</template>

<script>
import Article from '../components/main/Article.vue'

// @ is an alias to /src

export default {
  name: 'Home',
  components: {
    Article,
  }
}
</script>
