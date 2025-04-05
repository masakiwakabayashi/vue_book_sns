<script setup>
import { supabase } from '@/lib/supabaseClient';
import { onMounted, ref } from 'vue';

// https://www.googleapis.com/books/v1/volumes?q=intitle:吾輩は猫である

const searchQuery = ref('')


const search = () => {

}



</script>


<template>
  <div class="bg-blue-50 min-h-screen p-6">
    <div class="max-w-2xl mx-auto">
      <!-- Header -->
      <div class="bg-white shadow-md rounded-2xl p-6 mb-6">
        <h1 class="text-blue-600 text-3xl font-bold">書籍検索ページ</h1>
      </div>

      <!-- Search Section -->
      <div class="bg-white shadow-md rounded-2xl p-6 mb-6">
        <input 
          type="text" 
          v-model="searchQuery"
          @keyup.enter="searchBooks"
          placeholder="検索ワードを入力してください..." 
          class="w-full p-3 border rounded-lg mb-4 focus:outline-none focus:ring-2 focus:ring-blue-600"
        />
        <button
          class="w-full bg-blue-600 text-white font-semibold py-2 rounded-lg hover:bg-blue-700"
        >
          検索
        </button>
      </div>



    </div>
  </div>
</template>
