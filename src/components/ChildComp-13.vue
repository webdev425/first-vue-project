<script>
  export default {
    emits: ['response'],
    props: {
      msg: String
    },
    methods: {
      onInput(e) {
        this.$emit('response', e.target.value)
      }
    }
  }
</script>

<template>
  <input @input="onInput"   />
</template>