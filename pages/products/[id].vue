<template>
  <div>
    <h1>Product details {{ id }}</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis id in
      repellat voluptatem quos quaerat cupiditate! Doloribus magnam laboriosam
      iusto expedita, rerum dolore accusantium doloremque fugit libero sequi
      quibusdam saepe.
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;
</script>

<style lang="scss" scoped></style>
