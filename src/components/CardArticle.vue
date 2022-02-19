<template>
  <div class="container my-5 p-4 card">
    <h2>{{ title }}</h2>
    <div class="row">
      <div class="col">
        <p>Primary</p>
        <button class="btn btn-primary btn-sm">Primary</button>    
      </div>
      <div class="col">
        <p>Secondary</p>
        <button class="btn btn-secondary btn-sm">Secondary</button>
      </div>
      <div class="col">
        <p>Success</p>
        <button class="btn btn-success btn-sm">Success</button>
      </div>
      <div class="col">
        <p>Danger</p>
        <button class="btn btn-danger btn-sm">Danger</button>
      </div>
      <div class="col">
        <p>Warning</p>
        <button class="btn btn-warning btn-sm">Warning</button>
      </div>
      <div class="col">
        <p>Info</p>
        <button class="btn btn-info btn-sm">Info</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CardArticle',
  props: {
    title: String
  }
}
</script>

<style scoped>
p {
  margin-bottom: 1px;
}
</style>
