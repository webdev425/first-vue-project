<script>
  export default {
    data() {
      return {
        count: 0
      }
    },
    methods: {
      add() {
        this.count++
      }
    },
    watch: {
      count() {
        console.log(this.count)
      }
    }
  }
</script>

<template>
  <button @click="add">count is {{count}}</button>
</template>
