<template>
  <div class="layout">
    <px-main-menu class="main-menu" />
    <div class="content">
      <slot />
    </div>
    <px-side-nav class="side-nav" />
    <px-footer class="footer" />
  </div>
</template>

<script>
import PxMainMenu from "./PxMainMenu";
import PxSideNav from "./PxSideNav";
import PxFooter from "./PxFooter";
export default { components: { PxMainMenu, PxSideNav, PxFooter } };
</script>

<style scoped>
.layout {
  background-color: blue;
  position: relative;
  color: white;
}

.main-menu {
  position: fixed;
  top: 0px;
  left: 50%;
  transform: translateX(-50%);
  width: 500px;
  height: 40px;
  background-color: green;
}

.side-nav {
  position: fixed;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
  width: 40px;
  height: 200px;
  background-color: pink;
}

.footer {
  background-color: purple;
  width: 500px;
  height: 40px;
  transform: translateX(-50%);
  left: 50%;
  position: fixed;
  bottom: 0;
}
</style>
