<template>
  <div id="app">
    <AddTodo></AddTodo>
    <FilterTodos />
    <Todos />
  </div>
</template>

<script>
import Todos from "./components/Todos.vue";
import AddTodo from "./components/AddTodo.vue";
import FilterTodos from "./components/FilterTodos.vue";

export default {
  name: "App",
  components: {
    Todos,
    AddTodo,
    FilterTodos,
  },
};
</script>

<style>
#app {
  font-family: Montserrat, Helvetica, Arial, sans-serif;
}
body {
  line-height: 1.6;
  background: #e8f7f0;
}
.container {
  max-width: 1110px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
