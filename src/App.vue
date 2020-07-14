<template>
  <div id="app">
    <px-layout>
      <home />
      <cast />
    </px-layout>
  </div>
</template>

<script>
import PxLayout from "./layout/PxLayout";
import Home from "./components/Home";
import Cast from "./components/Cast";
export default {
  name: "App",
  components: { PxLayout, Home, Cast }
};
</script>

<style>
@font-face {
  font-family: "Bootle";
  src: url("./assets/fonts/BOOTLE__.TTF") format("truetype");
}

body {
  padding: 0;
  margin: 0;
  background-color: aliceblue;
}
</style>
