<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/">Nuxt app</NuxtLink>
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
      </nav>
    </header>

    <!-- Page content  -->
    <div>
      <slot></slot>
    </div>
  </div>
</template>

<style>
.router-link-exact-active {
  color: rgba(212, 57, 18, 0.753);
}
</style>
