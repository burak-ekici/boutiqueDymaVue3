<template>
  <div class="app-container">
    <TheHeader class="header"></TheHeader>
    <Shop class="shop"></Shop>
    <Cart class="cart"></Cart>
    <TheFooter class="footer"></TheFooter>
  </div>
</template>

<script lang="ts" setup>
import TheHeader from "./components/Header.vue";
import TheFooter from "./components/Footer.vue";
import Shop from "./components/Shop/Shop.vue";
import Cart from"./components/Cart/Cart.vue";
</script>

<style lang="scss">
@import "./assets/base.scss";
@import "./assets/debug.scss";

.app-container {
  display: grid;
  min-height: 100vh;
  grid-template-areas: "header header " "shop cart" "footer footer";
  grid-template-columns: 75% 25%;
  grid-template-rows: 48px auto 48px;
}

.header {
  grid-area: header;
}

.shop {
  grid-area: shop;
}

.cart {
  grid-area: cart;
}

.footer{
  grid-area: footer;
}
</style>
