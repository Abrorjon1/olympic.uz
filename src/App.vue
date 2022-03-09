<template>
  <Header />
  <Banner />
  <News />
  <Interview />
  <MediaFile />
  <Support />
  <SportTypes />
  <OlympGames />
  <Footer />
</template>

<script>
import Header from "./components/Header.vue";
import Banner from "./components/Banner.vue";
import News from "./components/News.vue";
import Interview from "./components/Interview.vue";
import MediaFile from "./components/MediaFile.vue";
import Support from "./components/Support.vue";
import SportTypes from "./components/SportTypes.vue";
import OlympGames from "./components/OlympGames.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Footer,
    OlympGames,
    SportTypes,
    Support,
    MediaFile,
    Interview,
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
