<template>
  <div id="bio">
    <img alt="Vue logo" src="../assets/logo.png">
    <p>My name is Rupert Saxton and I now live and work in Sydney</p>
  </div>
</template>

<script>
export default {
  name: 'Bio'
}
</script>

<style scoped>
#bio {
  width: 100%;
  height: 5rem;
  display: flex;
  align-items: center;
  margin-bottom: 2em;
}

img {
  width: 15%;
  min-width: 50px;
}
</style>
