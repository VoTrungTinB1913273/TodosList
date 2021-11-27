<template>
  <div>
    <div>
      <TodosList />
      <TodosListV3 />
    </div>
  </div>
</template>

<script>
import TodosList from "./components/TodosList";
import TodosListV3 from "./components/TodosListV3";
export default {
  name: "App",
  components: {
    TodosList,
    TodosListV3,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  text-align: center;
}
</style>