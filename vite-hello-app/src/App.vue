<script>
import AppTitle from "../src/components/appTitle.vue";
import AppHero from "../src/components/AppHero.vue";
export default {
  name: "App",
  components: {
    AppTitle,
    AppHero,
  },
};
</script>

<template>
  <h1>Haliho</h1>
  <AppTitle />
  <AppHero />
</template>

<style>
body {
  background-color: #121212;
}
h1 {
  color: #8286f4;
}
</style>
