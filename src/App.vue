<template>
  <div>
    <button class="ustaad-btn">test</button>
  </div>
</template>

<script>
import { ustaadBtn } from "ustaad-btn";

export default {
  name: "App",
  mounted() {
    console.log(ustaadBtn);
    setTimeout(() => ustaadBtn(), 3000);
  },
};
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
