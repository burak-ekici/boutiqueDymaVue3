<template>
  <div class="product d-flex flex-column">
    <div class="product-image"></div>
    <div class="p-10 d-flex flex-column">
      <h4>MacBook Pro</h4>
      <p>
        Lorem, ipsum dolor sit amet consectetur laborum doloribus et saepe
        suscipit quod vero?
      </p>
      <div class="d-flex flex-row align-items">
        <strong class="flex-fill">prix: 1500 €</strong>
        <button class="btn btn-primary">Ajouter au panier</button>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup></script>

<style lang="scss" scoped>
.product {
  background-color: #fff;
  border: var(--border);
  border-radius : var(--border-radius);
  &-image{
    border-top-left-radius : var(--border-radius);
    border-top-right-radius : var(--border-radius);
    background-image: url('https://www.apple.com/newsroom/images/product/mac/standard/Apple_new-macbook-air-wallpaper-screen_03182020_big.jpg.large.jpg');
    height: 200px;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
  }
}
</style>
