<script setup lang="ts">
import Navbar from './Navbar.vue';

</script>

<template>
    <div class="bg-gray-100 h-[100vh]">
        <Navbar />
        <main>
            <router-view />
        </main>
  </div>
</template>