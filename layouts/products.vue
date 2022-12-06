<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container mx-auto p-4 flex justify-between">
        <NuxtLink to="/products" class="font-bold">Nuxt app store</NuxtLink>
      </nav>
    </header>

    <!-- Page content  -->
    <div class="container mx-auto p-4">
      <slot></slot>
    </div>
    <!-- Products footer -->
    <footer class="container mx-auto p-4 flex justify-between border-t-2">
      <ul class="flex gap-4">
        <li>
          <NuxtLink to="/"> Home </NuxtLink>
        </li>
        <li>
          <NuxtLink to="/about"> About </NuxtLink>
        </li>
        <li>
          <NuxtLink to="/products"> Products </NuxtLink>
        </li>
      </ul>
    </footer>
  </div>
</template>

<style>
.router-link-exact-active {
  color: rgba(212, 57, 18, 0.753);
}
</style>
