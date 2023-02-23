<script>
import ChildComp from "./components/ChildComp-13.vue"

export default {
  components: {
    ChildComp
  },
  data() {
    return {
      childMsg: ''
    }
  },
  methods: {
    onResponse(msg) {
      this.childMsg = msg
    }
  }
}
</script>

<template>
  <ChildComp @response="onResponse" />
  <p>{{childMsg}}</p>
</template>

