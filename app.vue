<template>
  <div class="min-h-screen bg-neutral-950 text-white font-sans">
    <!-- Header -->
    <header class="w-full border-b border-neutral-800 px-6 py-4 flex justify-between items-center">
      <NuxtLink to="/" class="text-xl font-bold text-white hover:text-blue-400 transition flex items-center space-x-3">
        <svg width="24" height="20" viewBox="0 0 39 33" fill="none" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6">
          <path d="M19.5 2H3L19.5 29.5L36 2H19.5Z" stroke="white" stroke-width="3"/>
        </svg>
        <span>DELTA</span>
      </NuxtLink>
      <nav class="space-x-4 text-sm">
        <NuxtLink to="/rules" class="hover:text-blue-400 transition">Правила</NuxtLink>
        <NuxtLink to="/resources" class="hover:text-blue-400 transition">Ресурсы</NuxtLink>
      </nav>
    </header>

    <!-- Page content -->
    <NuxtPage />

    <!-- Footer -->
    <footer class="border-t border-neutral-800 px-6 py-6 text-center text-neutral-500 text-sm">
      &copy; 2025 Delta SMP. Сделано с ❤️
    </footer>
  </div>
</template>

<script setup>
// Всё обрабатывается Nuxt'ом
</script>

<style>
/* Tailwind уже подключён через main.css */
</style>
