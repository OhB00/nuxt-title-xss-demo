<template>
  <div>What a simple page! Nothing can go wrong here.</div>
</template>

<script setup>
useHead({ title: "</title><img src=x onerror=alert('XSS!!')>" });
</script>
