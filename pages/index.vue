<template>
  <div>
    <Navbar />
    <header class="bg-gray-200 text-center py-20">
      <h1 class="text-4xl font-bold">Selamat Datang di Bakso Aan Muda</h1>
      <p class="text-lg mt-2">Nikmati bakso terbaik dengan harga terjangkau!</p>
    </header>
    <section class="p-6 text-center">
      <NuxtLink to="/products" class="bg-red-500 text-white px-6 py-3 rounded">
        Lihat Menu Bakso
      </NuxtLink>
    </section>
  </div>
</template>

<script setup>
import Navbar from '~/components/Navbar.vue';
</script>
