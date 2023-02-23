<script>
  export default {
    data() {
      return {
        counter: {
          count: 0
        }
      }
    },
    methods: {
      increment() {
        this.counter.count++
      }
    }
  }
</script>

<template>
  <p>Count is {{counter.count}}</p>
  <button @click="increment">Add</button>
</template>