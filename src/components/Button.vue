<script>
export default {
  name: "ButtonComponent",
  props: {
    name: {
      default: "Submit Button",
      type: String,
    },
  },
};
</script>

<template>
  <button class="loginbtn">{{ name }}</button>
</template>

<style></style>
