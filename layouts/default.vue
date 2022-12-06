<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container mx-auto p-4 flex justify-between">
        <NuxtLink to="/" class="font-bold">Nuxt app</NuxtLink>
        <ul class="flex gap-4">
          <li>
            <NuxtLink to="/"> Home </NuxtLink>
          </li>
          <li>
            <NuxtLink to="/about"> About </NuxtLink>
          </li>
          <li>
            <NuxtLink to="/products" class="btn"> Products </NuxtLink>
          </li>
        </ul>
      </nav>
    </header>

    <!-- Page content  -->
    <div class="cotainer mx-auto p-4">
      <slot></slot>
    </div>
  </div>
</template>

<style>
.router-link-exact-active {
  color: rgba(212, 57, 18, 0.753);
}
</style>
