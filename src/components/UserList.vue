<template>
  <ul class="item-main">
   <ListItem></ListItem>
 </ul>
</template>

<script>
import ListItem from './ListItem.vue'

export default {
  name:'UserList',
  components:{ListItem}
}
</script>

<style>
.item-main{
    margin-left: 0px;
    border:1px solid #ddd;
    border-radius: 2px;
    padding: 0px;
}
</style>