<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga,
      consequatur? Nam tenetur quod illo quam, repudiandae, voluptatibus ipsa
      quae quis laudantium deleniti, deserunt unde reiciendis cum hic minus
      aliquid nihil!
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;
definePageMeta({
  layout: "products",
});
</script>

<style scoped></style>
