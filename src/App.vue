<template>
  <div id="app">
    <Quote-Card></Quote-Card>
  </div>
</template>

<script>
import QuoteCard from "./components/quote-card/quote-card.component.vue";
export default {
  name: "app",
  components: {
    QuoteCard
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
