<script>
export default {
  name: "NavbarPage",
  data() {
    return {
      menubar: false,
    };
  },
  methods: {
    showmenubar() {
      this.menubar ? (this.menubar = false) : (this.menubar = true);
      console.log(this.menubar);
    },
  },
};
</script>

<template>
  <nav>
    <img @click="showmenubar()" src="../assets/align-right.svg" alt="" />

    <div
      :class="menubar ? 'show' : ''"
      :style="{ visibility: menubar ? 'visible' : 'hidden' }"
      class="offcanvas offcanvas-start"
    >
      <ul class="offcanvas-end">
        <li @click="showmenubar()">&times;</li>
        <li>one</li>
        <li>one</li>
        <li>one</li>
        <li>one</li>
        <li>one</li>
        <li>one</li>
      </ul>
    </div>
  </nav>
</template>

<style>
li {
  color: rgb(37, 139, 228);
}
</style>
