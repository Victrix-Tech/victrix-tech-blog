<template>
  <section class="w-[20vw] h-screen pt-14 pl-28 hidden sm:block">
    <!-- top-logo -->
    <!-- <img src="../assets/logo-white.png" class="w-[10rem] h-6" alt /> -->
    <span class="text-white text-2xl font-semibold">Victrix.Tech</span>

    <!-- navigation -->
    <div class="navigation pt-20">
      <ul>
        <li
          class="flex justify items-center px-6 py-2 hover:bg-white rounded-lg hover:text-primary text-white cursor-pointer"
        >
          <i class="pi pi-qrcode" style="font-size: 1rem"></i>
          <span class="text-lg ml-4">Blog</span>
        </li>
      </ul>
    </div>
  </section>
</template>
<script setup>
import "primeicons/primeicons.css";
</script>