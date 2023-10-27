<template>
  <v-container>
    <h1>Home Page</h1>
  </v-container>
</template>

<script setup>
useSeoMeta({
  title: "My Title",
  description: "My description",
});

onMounted(async () => {});
</script>

<style scoped>
.section-padding {
  padding-top: 50px;
}
</style>
