<script>
import AppTitle from "../src/components/appTitle.vue";
export default {
  name: "App",
  components: {
    AppTitle,
  },
};
</script>

<template>
  <h1>Haliho</h1>
  <AppTitle />
</template>

<style>
body {
  background-color: #121212;
}
h1 {
  color: #8286f4;
}
</style>
