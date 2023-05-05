<template>
  <div>What a simple page! Nothing can go wrong here.</div>
</template>

<script setup>
useHead({
  title:
    "</title><i>Now you've seen the payload, delete 'package-lock.json' and update Nuxt</i><img src=x style='display:none' onerror=alert('XSS!!')>",
});
</script>
