<template>
  <div class="TodoItem">
    <input type="checkbox" v-model="completed"/>
    <span>{{TodoItemName}}</span>
    <button>x</button>
  </div>
</template>
 
<script>
export default {
  name: 'TodoItem',
  props: {
       'TodoItemName': String,
       'completed':Boolean
    }
  }
  
</script>