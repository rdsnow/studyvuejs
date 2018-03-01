<template>
  <div id="home">
    <h1>{{title}}</h1>
    <users></users>
  </div>
</template>

<script>
  import Users from './Users'
  export default {
    name: "home",
    data() {
      return {title: "我的第一个脚手架项目"}
    },
    components: {
      users: Users
    }
  }
</script>

<style scoped>
  h1 {
    color: purple;
  }
</style>
