<template>
  <AppHeader></AppHeader>
  <div>
    {{ message }}
  </div>
  <button @click="showAlert">경고</button>
</template>

<script>
  // import 컴포넌트이름 from './컴포넌트 경로'
  import AppHeader from "./components/AppHeader.vue";

  export default {
    components: {
      // '컴포넌트이름': 컴포넌트이름
      // 'app-header': AppHeader,
      // 'AppHeader': AppHeader
      // AppHeader: AppHeader
      AppHeader
    },
    data() {
      return {
        message: 'hi'
      }
    },
    methods: {
      showAlert() {
        alert('hello')
      }
    }
  }
</script>

<style scoped>

</style>
