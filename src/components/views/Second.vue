<template>
  <div class="first-app">
    {{msg}}
    <router-link to="/first">去第一个页面</router-link>
  </div>
</template>
<script>
export default {
  name: "Second",
  data() {
    return {
      msg: "Welcome to SecondApp"
    };
  }
};
</script>
<style>
</style>