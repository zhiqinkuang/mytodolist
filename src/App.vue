<template>
  <div id="app">
  <div class="page-header">
  <h1>MyTodoList</h1>
 </div>
  <div class="container">

  <div class="panel panel-primary">
  <!-- Default panel contents -->
  <div class="panel-heading">盛年不再来，一日难再晨</div>
  <UserHeader></UserHeader>
   <UserList></UserList>
   <UserFooter></UserFooter>
  </div>
  </div>
    
   
  </div>
 
</template>

<script>
import UserList from './components/UserList.vue'
import UserHeader from './components/UserHeader.vue'
import UserFooter from './components/UserFooter.vue'


export default {
  name: 'App',
  components: {
    UserHeader,UserList,UserFooter
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}





</style>
