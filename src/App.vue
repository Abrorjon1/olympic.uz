<template>
  <Header />
  <Banner />
</template>

<script>
import Header from "./components/Header.vue";
import Banner from "./components/Banner.vue";

export default {
  name: "App",
  components: {
    Banner,
    Header,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
