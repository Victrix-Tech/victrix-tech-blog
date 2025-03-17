<template>
  <section class="h-screen overflow-hidden bg-white sm:rounded-l-[2rem] w-full sm:ml-4">
    <BlogNav />
    <BlogPost />
  </section>
</template>
<script setup>
import BlogNav from "./blog/BlogNav.vue";
import BlogPost from "./blog/BlogPost.vue";
</script>