<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
// import { supabase } from './lib/supabaseClient';

// console.log(supabase);
</script>

<template>
  <header class="bg-blue-600 text-white shadow-md">
    <div class="wrapper max-w-7xl mx-auto px-4 py-5">
      <nav class="flex justify-between items-center">
        <div class="text-3xl font-bold">
          <RouterLink
            to="/"
          >
            Book Land
          </RouterLink>
        </div>
        <div class="space-x-4 mr-4">
          <RouterLink
            to="/search/books"
            class="text-lg hover:text-blue-200 transition-colors duration-200"
          >
            Search
          </RouterLink>
          <!-- <RouterLink
            to="/ranking/user"
            class="text-lg hover:text-blue-200 transition-colors duration-200"
          >
            Ranking
          </RouterLink> -->
          <RouterLink
            to="/"
            class="text-lg hover:text-blue-200 transition-colors duration-200"
          >
            Home
          </RouterLink>
          <RouterLink
            to="/login"
            class="text-lg hover:text-blue-200 transition-colors duration-200"
          >
            Login
          </RouterLink>
        </div>
      </nav>
    </div>
  </header>
  <RouterView />
</template>
