<template>
  <div>
    <h2>About</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet illo
      exercitationem quae, in maxime quam incidunt repellat! Tenetur,
      perspiciatis ad!
    </p>
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugiat natus
      iure expedita perferendis officia corporis at eius sed perspiciatis amet.
      Temporibus earum nemo iste facere odit facilis sunt minima iure.
    </p>
    <div>{{ data }}</div>
  </div>
</template>

<script setup>

// const { data } = await useFetch('/api/ninja?name=Mario', {
//   method: 'post',
//   body: {
//     age: 30
//   }
// })

const { data } = await useFetch('/api/currency/ADA')

</script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}

p {
  margin: 20px 0;
}
</style>
