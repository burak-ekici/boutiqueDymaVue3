<template>
  <h1>Bonjour {{ name }}</h1>
</template>

<script lang="ts" setup>
import { ref } from "vue";

const name = ref("jean");
</script>

<style lang="scss">
@import "./assets/base.scss";
@import "./assets/debug.scss";
</style>
