<template>
  <section class="container">
    <img src="../assets/img/logo.png" alt="Nuxt.js Logo" class="logo" />
    <h1 class="title">
      Universal Vue.js Application Framework
    </h1>
    <nuxt-link class="button" to="/about">
      About page
    </nuxt-link>
  </section>
</template>

<script>
export default {
  mounted () {
    let files = require.context('~/posts', true, /^\.\/.*\.md$/)
    let filenames = files.keys()
    console.log(filenames)
  }
}
</script>

<style scoped>
.title
{
  margin: 50px 0;
}
</style>
