<template>
  <section class="bg-white dark:bg-gray-900">
    <div class="py-8 px-4 mx-auto max-w-screen-xl text-left lg:py-16">
      <h1
        class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white">
        My Experience
      </h1>
    </div>
    <div class="flex flex-col space-y-4 sm:flex-row sm:justify-center sm:space-y-0">
      <ProjectCard></ProjectCard>
    </div>
  </section>

</template>

<script setup>
import ProjectCard from '@/components/JobCard.vue';

</script>

<style></style>
