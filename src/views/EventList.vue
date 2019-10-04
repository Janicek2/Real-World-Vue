<template>
  <div>
    <h1>Event list</h1>
    <router-link :to="{ name: 'event-show', params: { id: '1' } }"
      >Event Show #1</router-link
    >
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
