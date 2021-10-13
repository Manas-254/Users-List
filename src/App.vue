<template>
  <div class="main">
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      checkedData: [],
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c502c;
  margin-top: 60px;
  background-color: lightgoldenrodyellow;
}
</style>
