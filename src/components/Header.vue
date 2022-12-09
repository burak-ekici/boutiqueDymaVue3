<template>
  <header class="px-20 d-flex flex-row align-items">
    <a href="#" class="d-flex flex-row mr-20">
      <img src="../assets/logo.svg" alt="" />
      <span class="logo">Logo</span>
    </a>
    <ul class="flex-fill d-flex flex-row">
      <li class="mr-10">
        <a href="#">Boutique</a>
      </li>
      <li>
        <a href="#">Admin</a>
      </li>
    </ul>
    <ul class="d-flex flex-row">
      <li  class="mr-10">
        <a href="#">Inscription</a>
      </li>
      <li>
        <a href="#">Connexion</a>
      </li>
    </ul>
  </header>
</template>

<script lang="ts" setup></script>

<style lang="scss" scoped>
header {
  background-color: var(--color-primary);
  a {
    color: var(--text-color-primary);
    img {
      width: 20px;
      margin-right: 10px;
    }
    .logo{
      font-weight: 700;
      font-size: 20px;
    }
  }
}
</style>
