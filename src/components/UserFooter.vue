<template>
  <div class="todo-footer">
    <label>
      <input type="checkbox">
    </label>
    <span>已完成0</span>
    <button class="btn btn-danger">清除已经完成的任务</button>
  </div>
</template>

<script>
export default {
 name:'UserFooter'
}
</script>

<style scoped>
.todo-footer {
 height: 40px;
 line-height: 40px;
 padding-left: 6px;
 margin-top:5px;
}
.todo-footer label{
  display: inline-block;
  margin-right: 20px;
  cursor: pointer;
}
.todo-footer label input{
 position:relative;
 top:-1px;
}
.todo-footer label input:focus{
  outline: none;
  border-color: rgba(82, 168, 236, 0.8);
  box-shadow: inset 0 1px 1px rgba(82, 168, 236, 0.8);
}
.todo-footer label input:focus{
  outline: none;
  border-color: rgba(82, 168, 236, 0.8);
  box-shadow: inset 0 1px 1px rgba(82, 168, 236, 0.8);
}
.todo-footer button{
  float:right;
}
</style>