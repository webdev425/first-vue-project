<script>
import ChildComp from "./components/ChildComp-12.vue"

export default {
  components: {
    ChildComp
  },
  data() {
    return {
      greetings: "Hello"
    }
  }
}
</script>

<template>
  <ChildComp :msg="greetings" />
</template>