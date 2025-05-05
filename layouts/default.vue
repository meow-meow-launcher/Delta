<template>
    <div class="min-h-screen bg-neutral-950 text-zinc-100 font-sans">
      <header class="border-b border-zinc-800">
        <div class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
          <h1 class="text-xl font-bold tracking-tight text-white">
            🌐 Minecraft Server
          </h1>
          <nav class="space-x-6 text-zinc-300">
            <NuxtLink to="/" class="hover:text-blue-500 transition">Главная</NuxtLink>
            <NuxtLink to="/rules" class="hover:text-blue-500 transition">Правила</NuxtLink>
            <NuxtLink to="/resources" class="hover:text-blue-500 transition">Ресурсы</NuxtLink>
          </nav>
        </div>
      </header>
  
      <main class="max-w-4xl mx-auto px-4 py-10">
        <slot />
      </main>
  
      <footer class="border-t border-zinc-800 text-zinc-500 text-sm mt-10 py-6 text-center">
        &copy; {{ new Date().getFullYear() }} Minecraft Server. Все права защищены.
      </footer>
    </div>
  </template>
  