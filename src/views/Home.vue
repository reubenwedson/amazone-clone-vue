<template>
  <div>
    <Header />
    <div class="home">
      <div class="home__container">
        <img
          class="home__image"
          src="../assets/main_banner.jpg"
          alt="home_banner"
        />
      </div>
    </div>
  </div>
</template>

<script>
import Header from "../components/navigation/Header";
export default {
  name: "Home",
  components: { Header }
};
</script>

<style scoped>
.home {
  display: flex;
  justify-content: center;
  margin: 0 auto;
  max-width: 1500px;
}

.home__container {
  overflow: hidden;
}

.home__row {
  display: flex;
  z-index: 1;
  margin: 0 5px;
}

.home__image {
  width: 100%;
  z-index: -1;
  margin: 0 0 -360px;
  /* mask-image: linear-gradient(to bottom, rgba(0,0,0,1), rgba(0, 0, 0, 0)); */
}
</style>
