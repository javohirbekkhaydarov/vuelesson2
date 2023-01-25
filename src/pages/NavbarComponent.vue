<script>
export default {
  name: "NavbarComponent",
  data() {
    return {
      showmenu: false,
    };
  },
  methods: {
    showFunction() {
      this.showmenu ? (this.showmenu = false) : (this.showmenu = true);
      console.log(this.showmenu);
    },
  },
};
</script>

<template>
  <nav class="nav">
    <div class="logo p-4">
      <img
        class="logoimg"
        @click="showFunction"
        src="../assets/align-left.svg"
        alt=""
      />
    </div>
    <div
      class="menubar offcanvas offcanvas-end"
      :class="showmenu ? 'show' : ''"
      :style="{ visibility: showmenu ? 'visible' : 'hidden' }"
    >
      <div class="close">
        <img @click="showFunction" src="../assets/x.svg" alt="" />
      </div>
      <ul>
        <li>O nas</li>
        <li>Kontakt</li>
      </ul>
    </div>
  </nav>
</template>

<style>
.nav {
  background: #000;
  display: flex;
  flex-direction: column;
  justify-content: start;
}

.logoimg {
  transform: rotate(180deg);
  cursor: pointer;
}
.menubar {
  background: rgb(71, 70, 70);
}
ul {
  color: rgb(178, 170, 170);
}

.close {
  cursor: pointer;
  display: flex;
  justify-content: end;
  padding: 20px;
}
</style>
