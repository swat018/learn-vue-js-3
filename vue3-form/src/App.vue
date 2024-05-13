<template>
  <form action="">
    <div>
      <label for="userId">ID:</label>
      <input id="userID" type="text" v-model="username">
    </div>
    <div>
      <label for="password">PW:</label>
      <input type="text" v-model="password">
    </div>
    <button type="submit">로그인</button>
  </form>
</template>

<script>
  export default {
    data() {
      return {
        username: '',
        password: ''
      }
    },
  }
</script>

<style scoped>

</style>
