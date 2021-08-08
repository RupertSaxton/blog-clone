<template>
  <div id="articles">
    <div 
      v-for="article in articles"
      :key="article.title">
      <article-button :title="article.title" :lede="article.lede"></article-button>
    </div>
  </div>
</template>

<script>
import ArticleButton from './ArticleButton.vue'

export default {
  components: { ArticleButton },
  name: 'ArticleLinks',
  data() {
    return {
      articles: [
        { title: 'What', lede: 'is there' },
        { title: 'World', lede: 'Here is something else' },
        { title: 'It is me', lede: 'Life should be fun for everyone' },
      ]
    }   
  }
}
</script>
