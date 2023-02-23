<script>
  export default {
    data() {
      return {
        titleClass: 'title'
      }
    }
  }
</script>

<template>
  <h1 :class="titleClass">Hello World</h1>
</template>

<style>
  .title {
    color: red
  }
</style>