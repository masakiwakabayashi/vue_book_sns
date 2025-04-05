<script setup>
import { supabase } from '@/lib/supabaseClient';
import { onMounted, ref } from 'vue';

const imageUrl = ref(null);

// TODO: これはあとで別ファイルに移す
const getPublicUrl = (bucket, path) => {
  const { data } = supabase.storage.from(bucket).getPublicUrl(path)
  return data.publicUrl
}

onMounted(() => {
  // 例: 'images' バケットに 'my-folder/my-image.jpg' がある場合
  imageUrl.value = getPublicUrl('test', '1.png')
})

</script>


<template>
  <div class="bg-blue-50 min-h-screen p-6">
    <div class="max-w-2xl mx-auto">
      <!-- Header -->
      <div class="bg-white shadow-md rounded-2xl p-6 mb-6">
        <h1 class="text-blue-600 text-3xl font-bold">タイムライン</h1>
      </div>

      <!-- 画像の表示テスト -->
      <div class="mb-6">
        <img v-if="imageUrl" :src="imageUrl" alt="My test Image" />
      </div>
      <!-- Post Input Section -->
      <div class="bg-white shadow-md rounded-2xl p-4 mb-6">
        <router-link
          to="/post/create"
          class="block w-full bg-blue-600 text-white py-3 rounded-lg text-center hover:bg-blue-700 transition"
        >
          投稿する
        </router-link>
      </div>

    </div>
  </div>
</template>
