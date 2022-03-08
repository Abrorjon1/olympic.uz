<template>
  <Header />
  <Banner />
  <News />
</template>

<script>
import Header from "./components/Header.vue";
import Banner from "./components/Banner.vue";
import News from "./components/News.vue";

export default {
  name: "App",
  components: {
    News,
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
