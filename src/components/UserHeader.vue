<template>
   <div>
    <input type="text" id="task-input" placeholder="请输入你的任务,回车确定">
   </div>
</template>

<script>
export default {
  name:'UserHeader'
}
</script>

<style scoped>
#task-input{
   width: 100%;
   height: 40px;
   line-height: 40px;
   font-size:16px;
   padding: 4px 7px;
}
#task-input:focus{
  outline:none;
  border-color: rgba(82, 168, 236, 0.8);
  box-shadow: inset 0 1px 1px rgba(82, 168, 236, 0.8);
}
</style>