<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  components: {
    AppTitle,
    AppHero,
  },
};
</script>

<template>
  <AppTitle></AppTitle>
  <AppHero></AppHero>
</template>

<style>
@import url("./assets/main.css");
</style>
