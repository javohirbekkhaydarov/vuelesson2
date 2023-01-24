<script>
import Button from "./components/Button.vue";
export default {
  name: "App",
  data() {
    return {
      count: 0,
    };
  },
  components: {
    Button,
  },
  methods: {
    onSubmit() {
      console.log("submitted");
    },
  },
};
</script>

<template>
  <h1>hi</h1>
  <div class="container">
    <Button name="Login" />
    <Button class="signup" name="Submit" />
    <p>{{ count }}</p>
    <button @click="count++">+</button>

    <form @click.prevent="onSubmit">
      <input type="text" name="name" placeholder="your name" />

      <button class="btn">submit 1</button>
      <button class="btn">submit 2</button>
      <button id="btn">submit 3</button>
    </form>
  </div>
</template>

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
