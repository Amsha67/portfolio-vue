<template>
  <div id="app">
    <portfolio />
    <header />
    <footer />
  </div>
</template>

<script>
import portfolio from "./components/portfolio.vue";
import header from "./components/header.vue";
import footer from "./components/footer.vue";

export default {
  components: {
    portfolio,
     header,
    footer,  
  },
};
</script>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
}
</style>