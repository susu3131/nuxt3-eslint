<script lang="ts" setup>
const id = 123;
const id2 = 456;
</script>

<template>
  <div>
    <p>product</p>
    <nuxt-link :to="`/product/${id}`" style="margin-right: 8px">商品細節1</nuxt-link>
    <nuxt-link :to="`/product/${id2}`">商品細節2</nuxt-link>
    <NuxtPage />
  </div>
</template>

<style scoped></style>
