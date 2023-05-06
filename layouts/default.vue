<template>
  <div>
    <header>
      <nuxt-link to="/">Nuxt toJo</nuxt-link>
      <nav>
        <ul>
          <li><nuxt-link to="/">Home</nuxt-link></li>
          <li><nuxt-link to="/products">Product</nuxt-link></li>
          <li><nuxt-link to="/about">About</nuxt-link></li>
        </ul>
        <a href="/about">normal route-- about</a>
      </nav>
    </header>
    <!-- out the page content  -->
    <div>
      <slot></slot>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.router-link-exact-active {
  color: aqua;
}
</style>
