<script>
  export default {
    data() {
      return {
        visible: true
      }
    },
    methods: {
      toggle() {
        this.visible = !this.visible
      }
    }
  }
</script>

<template>
  <p v-if="visible">Visible is true</p>
  <p v-else>Visible is false</p>
  <button @click="toggle">Toggle</button>
</template>