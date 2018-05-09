<template>
  <div id="app">
    <avatar/>
  </div>
</template>

<script>
import Avatar from "./components/Avatar";

export default {
  name: "App",
  components: {
    Avatar
  }
};
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
