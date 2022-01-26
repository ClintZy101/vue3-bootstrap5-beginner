<template>
  <TopBar />
  <Jumbotron />
  <CTA />
  <Cards />
</template>

<script>
import TopBar from "./components/TopBar.vue";
import Jumbotron from "./components/Jumbotron.vue";
import CTA from "./components/CTA.vue";
import Cards from "./components/Cards.vue";

export default {
  name: "App",
  components: {
    TopBar,
    Jumbotron,
    CTA,
    Cards,
  },
};
</script>

<style>
</style>
