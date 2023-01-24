
<!-- ! options api -->

<script>
export default {
  name: "CounterComponent",
  data() {
    return {
      count: 0,
    };
  },
};
</script>

<template>
  <p>{{ count }}</p>
  <button @click="count++">+</button>
</template>

<!-- ! Composition api -->

<!-- <script setup>
import { ref } from "vue";
const count = ref(0);
</script>

<template>
  <h1>hi this is counter</h1>
  {{ count }}
  <button @click="count++">+</button>
</template> -->
