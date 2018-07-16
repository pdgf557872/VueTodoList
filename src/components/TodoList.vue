<template>
  <ul>
    <li><TodoItem TodoItemName="Item 1" v-bind:completed=false></TodoItem></li>
    <li><TodoItem TodoItemName="Item 2" v-bind:completed=false></TodoItem></li>
    <li><TodoItem TodoItemName="Item 3" v-bind:completed=true></TodoItem></li>
  </ul>
</template>
 
<script>
import TodoItem from '../components/TodoItem.vue'


console.log(this.props)
export default {  
    name: 'TodoList',
    components: {
      'TodoItem':TodoItem
    }
  }

</script>