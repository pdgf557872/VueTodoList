<template>
  <div id="app">
    <TodoHeader/>
    <InputField/>
    <TodoList/>
  </div>
</template>

<script>
import InputField from './components/InputField.vue'
import TodoHeader from './components/TodoHeader.vue'
import TodoList from './components/TodoList.vue'


export default {
  name: 'app',
  components: {
    TodoHeader,
    InputField,
    TodoList,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  margin-top: 60px;
}
</style>
