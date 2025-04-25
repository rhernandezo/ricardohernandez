<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <img
      alt="Ricardo Hernández logo"
      class="logo"
      src="@/assets/logo_rh_black.png"
      width="40"
      height="40"
    />
    <nav>
      <RouterLink to="/">Home</RouterLink>
    </nav>
  </header>

  <RouterView />
</template>

<style scoped></style>
