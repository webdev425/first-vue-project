<script>
  export default {
    data() {
      return {
        todoList: ["A", "B", "C", "A"]
      }
    },
    methods: {
      remove(todo) {
        this.todoList = this.todoList.filter((t) => t !== todo)
      }
    }
  }
</script>

<template>
  <p v-for="todo in todoList" :key="todo">
    {{todo}}
    <button @click="remove(todo)">X</button>
  </p>

</template>