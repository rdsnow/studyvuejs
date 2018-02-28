<template>
  <div id="app">
    <h1>{{title}}</h1>
    <users></users>
  </div>
</template>

<script>
  import Users from './components/Users'
  export default {
    name: 'App',
    data() {
      return {title: "我的第一个脚手架项目"}
    },
    components:{
      users:Users
    }
  }
</script>

<style>
</style>
