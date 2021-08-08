<template>
  <h1>Blog</h1>
  <bio></bio>
  <article-links></article-links>
</template>

<script>
import ArticleLinks from './components/ArticleLinks.vue'
import Bio from './components/Bio.vue'

export default {
  name: 'App',
  components: {
    ArticleLinks,
    Bio
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  display: flex;
  flex-direction: column;
  width: 50%;
  margin: auto;
}

#app h1 {
  font-size: 4rem;
  line-height: 4.5rem;
  font-weight: 900;
}
</style>
