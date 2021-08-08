<template>
  <div id="article-button">
    <h2>{{ title }}</h2>
    <h3>{{ lede }}</h3>
  </div>
</template>

<script>
export default {
  name: 'ArticleButton',
  props: {
    title: String,
    lede: String,
  }
}
</script>

<style scoped>
h3 {
  color: rgb(112, 109, 109);
}

#article-button {
  padding: 22px;
  transition: transform 0.3s;
}

#article-button:hover {
  border: 2px solid rgb(196, 188, 188);
  border-radius: 15px;
  padding: 20px;
  transform: scale(1.02);
}
</style>