<script setup lang="ts"></script>

<template>
  <footer
    class="flex flex-col lg:flex-row items-center justify-between p-4 mx-auto max-w-7xl mt-16 border-t-2 border-gray-700 "
  >
    <div>
      <h1 class="text-2xl font-bold text-black dark:text-white">
        Chafik
        <span class="text-blue-800">Dev</span>
      </h1>
    </div>

    <div class="mt-4 lg:mt-0">
        <p class="text-black dark:text-white text-sm font-normal">Copyrights &copy; {{ new Date().getFullYear() }}</p>
    </div>
  </footer>
</template>
