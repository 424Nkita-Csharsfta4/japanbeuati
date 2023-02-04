<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Content from './components/Content.vue'
</script>

<template>
  
      <nav class="bg-black ">
        <div class="container flex flex-col items-center p-4 mx-auto">
            
            <div class="flex items-center justify-center mt-6 text-gray-600 capitalize dark:text-gray-300">
              <RouterLink to="/" class="mx-2 text-gray-800 border-b-2 border-blue-500 dark:text-gray-200 sm:mx-6">Главное</RouterLink>
              <RouterLink to="/about" class="mx-2 border-b-2 border-transparent hover:text-gray-800 dark:hover:text-gray-200 hover:border-blue-500 sm:mx-6">Аниме</RouterLink>
              <RouterLink to="/news" class="mx-2 border-b-2 border-transparent hover:text-gray-800 dark:hover:text-gray-200 hover:border-blue-500 sm:mx-6">Новости</RouterLink>
            </div>
        </div>
    </nav>
  <RouterView />
  <Content/>
</template>


