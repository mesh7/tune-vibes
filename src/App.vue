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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
