<template>
  <div>
    <Box />
    <Active />
  </div>
</template>

<script>
import Box from "./components/box.vue";
import Active from "./components/active.vue";

export default {
  name: "App",
  components: {
    Box,
    Active,
  },
};
</script>

<style>
</style>
