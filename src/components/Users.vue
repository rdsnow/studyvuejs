<template>
  <div class="users">
    <ul>
      <li v-for="user in users">
        {{user}}
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    name: "users",
    data() {
      return {users: ["王林", "李庞", "王岐山", "黄颖"]}
    }
  }
</script>

<style scoped>

</style>
