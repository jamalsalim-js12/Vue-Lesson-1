<script>
export default {
  data() {
    return {
      isOpen: opened,
    };
  },
};
</script>

<template>
  <main>
    <div v-if="isOpen">
      <h1>This is opened</h1>
    </div>

    <div v-else>
      <h1>This is closed</h1>
    </div>
  </main>
</template>

<style scoped></style>
