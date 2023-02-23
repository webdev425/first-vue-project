<script>
  export default {
    data() {
      return {
        text: ""
      }
    },
    methods: {
      onInput(e) {
        this.text = e.target.value
      }
    }
  }
</script>

<template>
  <input :value="text" @input="onInput" />
  <p>{{text}}</p>
</template>