<template>
  <div class="TodoHeader">
    <h1>{{title}}</h1>
    <span>哈囉，{{username}}：你有 {{todoCount}} 項未完成待辦事項</span>
  </div>
</template>
 
<script>
export default {
  name: 'TodoHeader',
  props:{
    title:{
      type:String,
      default: '我的待辦清單'
    },
    username:{
      type:String,
      default: 'Guest'
    },
    todoCount:{
      type:Number,
      default: 0
    }
  },
  data () {
    return {
          TodoHeader:'TodoHeader'
				}
    }
  }

</script>