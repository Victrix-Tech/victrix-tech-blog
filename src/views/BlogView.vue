<script setup>
import Blog from "@/components/Blog.vue";
import Sidebar from "@/components/Sidebar.vue";
import MobNav from "@/components/MobNav.vue";
</script>
<template>
  <main class="h-screen bg-primary overflow-x-hidden sm:flex">
    <!-- Desktop-nav -->
    <Sidebar />
    <!-- Mobile-nav -->
    <MobNav />
    <Blog />
  </main>
</template>