<script setup>
import { RouterLink, RouterView } from 'vue-router'
//import HelloWorld from '@/components/HelloWorld.vue'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/"></RouterLink>
        <RouterLink to="/gallery"></RouterLink>
        <RouterLink to="/add"></RouterLink>
      </nav>
    </div>
  </header>
  <RouterView />
</template>







