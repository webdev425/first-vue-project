<script>
  export default {
    mounted() {
      setTimeout(() => {
        this.$refs.p.textContent = "mounted"
      }, 3000)
    }
  }
</script>

<template>
  <p ref="p">Hello</p>
</template>