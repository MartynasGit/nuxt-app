<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/products">Nuxt app store</NuxtLink>
      </nav>
    </header>

    <!-- Page content  -->
    <div>
      <slot></slot>
    </div>
    <!-- Products footer -->
    <footer>
      <ul>
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
