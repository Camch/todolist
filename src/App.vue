<template>
  <div>
    <TodoList />
  </div>
</template>

<script>
import TodoList from "./components/TodoList.vue";

export default {
  name: "App",
  components: {
    TodoList,
  },
};
</script>

<style>
body {
  background-color: #424242;
  color: aliceblue;
}
</style>
