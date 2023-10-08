<template>
  <div>
    
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
    <div style="background: #ffcaca; padding: 10px; width: 200px">
      {{ test }}
    </div>
  </div>
</template>

<script setup>
const test = await $fetch("/api/test");
</script>
