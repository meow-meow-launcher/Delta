<template>
    <div class="p-4 bg-zinc-900 rounded-lg border border-zinc-800">
      <p class="text-sm text-zinc-400 uppercase mb-1">[{{ number }}]</p>
      <h3 class="text-lg font-semibold text-white">{{ title }}</h3>
      <p class="text-zinc-400 mt-1">{{ description }}</p>
      <p class="text-red-400 text-sm italic mt-2">{{ punishment }}</p>
    </div>
  </template>
  
  <script setup>
  defineProps({
    number: String,
    title: String,
    description: String,
    punishment: String,
  })
  </script>
  