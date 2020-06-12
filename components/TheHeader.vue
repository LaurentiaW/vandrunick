<template>
  <header class="main-header">
    <p class="container display">VANDRUNICK</p>
    <p class="container display smaller">love&relove</p>
    <nav class="main-nav container">
      <ul class="nav-links">
        <nuxt-link to="/" tag="li"><a>Home</a></nuxt-link>
        <nuxt-link to="/pcp" tag="li"><a>Products</a></nuxt-link>
        <nuxt-link to="/about" tag="li"><a>About</a></nuxt-link>
        <nuxt-link to="/contact" tag="li"><a>Contact</a></nuxt-link>
      </ul>
    </nav>
  </header>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style scoped></style>
