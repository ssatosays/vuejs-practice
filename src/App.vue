<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <CardArticle title="First Article"/>
  <CardArticle title="Second Article"/>
  <CardArticle title="Third Article"/>
  <CardArticle title="Fourth Article"/>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import CardArticle from './components/CardArticle.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    CardArticle
  }
}
</script>

<style>
#app {
  color: #2c3e50;
}
</style>
