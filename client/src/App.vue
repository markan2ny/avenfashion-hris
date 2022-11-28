<template>
  <Header />
  <main class="container mx-auto">
    <router-view />
  </main>
</template>
<script setup>
import Header from '@/components/Header.vue';
import { RouterView } from 'vue-router';
</script>