<template>
  <div id="app">
    <NavBar />
    <SlideShow />
    <MainSection />
    <CustomerExp />
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import SlideShow from "./components/SlideShow.vue";
import MainSection from "./components/MainSection.vue";
import CustomerExp from "./components/CustomerExp";

export default {
  name: "App",
  components: {
    NavBar,
    SlideShow,
    MainSection,
    CustomerExp,
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
  /* margin-top: 60px; */
}
</style>
