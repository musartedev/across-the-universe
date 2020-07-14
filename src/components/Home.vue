<template>
  <div class="home">
    <div class="home__content">
      <figure>
        <img src="../assets/mainlogo.png" />
      </figure>
      <h1 class="home__title">Across The Universe</h1>
    </div>
  </div>
</template>

<style scoped>
.home {
  background: url("../assets/universe.jpg");
  background-repeat: repeat;
  height: 100%;
}

.home__content {
  width: 100%;
  max-width: 1024px;
  height: 100%;
  margin: auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.home__title {
  font-family: "Bootle", "Helvetica", "sans-serif";
  font-size: 60px;
}

figure {
  width: 50%;
}

img {
  width: 100%;
}
</style>
