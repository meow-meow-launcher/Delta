<template>
    <div class="min-h-screen bg-neutral-950 text-white">
      <section class="max-w-4xl mx-auto py-16 px-6">
        <h1 class="text-4xl font-bold mb-4">Добро пожаловать на сервер Delta SMP</h1>
        <p class="text-lg mb-6 text-neutral-400">
          Здесь вы найдете правила, ссылки на ресурсы и важную информацию для игроков. Пожалуйста, ознакомьтесь со всем перед игрой.
        </p>
  
        <div class="grid md:grid-cols-2 gap-6">
          <NuxtLink to="/rules" class="group p-6 border border-neutral-800 rounded-2xl hover:bg-neutral-900 transition">
            <h2 class="text-xl font-semibold mb-2 group-hover:text-white text-neutral-300">📜 Правила</h2>
            <p class="text-sm text-neutral-400">Все правила сервера и модов в одном месте.</p>
          </NuxtLink>
  
          <NuxtLink to="/resources" class="group p-6 border border-neutral-800 rounded-2xl hover:bg-neutral-900 transition">
            <h2 class="text-xl font-semibold mb-2 group-hover:text-white text-neutral-300">🔗 Ресурсы и ссылки</h2>
            <p class="text-sm text-neutral-400">Сборка, веб-карта, полезные ссылки для игры.</p>
          </NuxtLink>
        </div>
  
        <footer class="mt-16 border-t border-neutral-800 pt-6 text-sm text-neutral-500 text-center">
          &copy; 2025 Delta SMP. Все права защищены.
        </footer>
      </section>
    </div>
  </template>
  
  <script setup>
  // пока без логики
  </script>
  