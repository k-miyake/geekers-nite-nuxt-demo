<script setup>
const route = useRoute()
const pageId = route.params.id
</script>

<template>
  <div>
    <h2>ページID: {{ pageId }}</h2>
  </div>
</template>
