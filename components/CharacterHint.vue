<script setup lang="ts"></script>

<template>
  <!-- Character image -->
  <div
    class="w-[75px] h-[75px] rounded border-2 border-gray-700 text-gray-900 font-bold text-sm flex justify-center items-center text-center"
  >
    <NuxtImg src="/imgs/NefertariVivi.png" alt="Character logo" />
  </div>
  <!-- Gender -->
  <div
    class="bg-green-600 w-[75px] h-[75px] rounded border-2 border-green-800 text-gray-900 font-bold text-sm flex justify-center items-center text-center"
  >
    Female
  </div>
  <!-- Affiliation -->
  <div
    class="bg-green-600 w-[75px] h-[75px] rounded border-2 border-green-800 text-gray-900 font-bold text-sm flex justify-center items-center text-center"
  >
    <slot />
  </div>
  <!-- Devil Fruit -->
  <div
    class="bg-red-600 w-[75px] h-[75px] rounded border-2 border-red-800 text-gray-900 font-bold text-sm flex justify-center items-center text-center"
  >
    None
  </div>
  <!-- Haki -->
  <div
    class="bg-red-600 w-[75px] h-[75px] rounded border-2 border-red-800 text-gray-900 font-bold text-sm flex justify-center items-center text-center"
  >
    None
  </div>
  <!-- Latest Bounty -->
  <div
    class="bg-yellow-500 w-[75px] h-[75px] rounded border-2 border-yellow-600 text-gray-900 font-bold text-sm flex justify-center items-center text-center"
  >
    X
  </div>
  <!-- Height -->
  <div
    class="bg-red-600 w-[75px] h-[75px] rounded border-2 border-red-800 text-gray-900 font-bold text-sm flex justify-center items-center text-center"
  >
    None
  </div>
  <!-- Origin -->
  <div
    class="bg-green-600 w-[75px] h-[75px] rounded border-2 border-green-800 text-gray-900 font-bold text-sm flex justify-center items-center text-center"
  >
    Grand Line
  </div>
  <!-- Debut Saga -->
  <div
    class="bg-red-600 w-[75px] h-[75px] rounded border-2 border-red-800 text-gray-900 font-bold text-sm flex justify-center items-center text-center"
  >
    Arabasta
  </div>
</template>
