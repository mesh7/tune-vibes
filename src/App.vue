<template>
  <div id="app">
    <TuneVibes msg="OCEAN" />
  </div>
</template>

<script>
import TuneVibes from "./components/TuneVibes.vue";

export default {
  name: "App",
  components: {
    TuneVibes,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;500;700&display=swap");

#app {
  font-family: Poppins, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
