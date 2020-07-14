<template>
  <div id="app">
    <px-layout>
      Content
    </px-layout>
  </div>
</template>

<script>
import PxLayout from "./layout/PxLayout";
export default {
  name: "App",
  components: { PxLayout }
};
</script>

<style>
body {
  padding: 0;
  margin: 0;
  background-color: aliceblue;
}
</style>
