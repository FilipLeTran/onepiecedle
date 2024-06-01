<script setup lang="ts">
const headers = ref([
  {
    title: "Character",
  },
  {
    title: "Gender",
  },
  {
    title: "Affiliation",
  },
  {
    title: "Devil Fruit",
  },
  {
    title: "Haki",
  },
  {
    title: "Latest Bounty",
  },
  {
    title: "Height",
  },
  {
    title: "Origin",
  },
  {
    title: "First Saga",
  },
]);
</script>

<template>
  <div class="flex gap-1 my-2">
    <div
      v-for="header in headers"
      :key="header.title"
      class="w-[75px] h-[75px] border-b-4 border-b-black text-center flex justify-center items-center"
    >
      {{ header.title }}
    </div>
  </div>
</template>
