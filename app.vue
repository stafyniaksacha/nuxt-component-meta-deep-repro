<script setup lang="ts">
const meta = await useComponentMeta('UButton')
</script>

<template>
  <div>
    <UButton>Button</UButton>
    <pre>{{ meta.meta }}</pre>
  </div>
</template>
