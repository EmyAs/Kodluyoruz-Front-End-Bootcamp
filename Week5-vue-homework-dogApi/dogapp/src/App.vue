<template>
  <div id="app">
    <Dog />
  </div>
</template>

<script>
import Dog from "@/components/Dog";
export default {
  name: "app",
  components: { Dog }
};
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
