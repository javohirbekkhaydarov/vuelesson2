<script>
import HomePage from "./components/HomePage.vue";
import CounterComponent from "./components/CunterComponent.vue";
export default {
  name: "App",

  components: {
    HomePage,
    CounterComponent,
  },
};
</script>

<template>
  <div class="app">
    <HomePage />
    <CounterComponent />
  </div>
</template>
