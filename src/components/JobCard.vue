<template>
  <div
    class="flex flex-col items-center bg-white border border-gray-200 rounded-lg shadow md:flex-row md:max-w-xl hover:bg-gray-100 dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700">
    <img class="object-cover w-full rounded-t-lg h-96 md:h-auto md:w-48 md:rounded-none md:rounded-s-lg" src="" alt="">
    <div class="flex flex-col justify-between p-4 leading-normal">
      <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">{{ title }}
      </h5>
      <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">{{ timeRange }}</p>

      <li v-for="item in items" class="font-normal text-gray-700 dark:text-gray-400">
        {{ item.message }}
      </li>


    </div>
  </div>
</template>

<script setup>
import { ref, onMounted } from 'vue'
const title = "Fullstack Software Engineer I Vancouver"
const timeRange = "Feb 2023 - Feb 2024"
const tools = ["Java", "Spring", "VueJS", "AWS"]

const items = [{ message: 'Experience 1' }, { message: 'Experience 2' }]

</script>

<style></style>
