<template>
  <div>
    <Header />
    <div class="checkout">
      <div class="checkout__left">
        <img
          src="../assets/checkout_banner.jpg"
          alt="ad_banner"
          class="checkout__ad"
        />
      </div>
    </div>
  </div>
</template>

<script>
import Header from "../components/navigation/Header";
export default {
  name: "Checkout",
  components: { Header }
};
</script>

<style scoped>
.checkout {
  display: flex;
  padding: 20px;
  background-color: #ffffff;
  height: max-content;
}

.checkout__ad {
  width: 100%;
  margin: 0 0 10px;
}

.checkout__title {
  margin: 0 10px 0 0;
  padding: 10px;
  border-bottom: 1px solid #d3d3d3;
}
</style>
