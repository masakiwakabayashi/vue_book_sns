<template>
  <div class="bg-blue-50 min-h-screen p-6">
    <div class="max-w-2xl mx-auto">
      <!-- Header -->
      <div class="bg-white shadow-md rounded-2xl p-6 mb-6">
        <h1 class="text-blue-600 text-3xl font-bold">タイムライン</h1>
      </div>

      <!-- Post Input Section -->
      <div class="bg-white shadow-md rounded-2xl p-4 mb-6">
        <button class="w-full bg-blue-600 text-white py-3 rounded-lg hover:bg-blue-700 transition">
          投稿する
        </button>
      </div>

      <!-- Timeline Posts -->
      <div class="space-y-6">
        <!-- Post 1 -->
        <div class="bg-white shadow-md rounded-2xl p-4">
          <div class="flex gap-4">
            <img src="https://via.placeholder.com/50" alt="User Avatar" class="w-12 h-12 rounded-full" />
            <div class="w-full">
              <div class="flex justify-between items-center">
                <div>
                  <span class="inline-block bg-blue-100 text-blue-600 font-semibold px-2 py-1 rounded-full mt-2 mr-3">
                    本の感想
                  </span>
                  <span class="font-bold text-blue-600">山田太郎</span>
                  <span class="text-gray-500 text-sm ml-2">@taro_yamada</span>
                </div>
                <span class="text-gray-400 text-sm">1時間前</span>
              </div>
              <p class="text-gray-800 mt-2">ITエンジニアのための機械学習理論入門</p>
              <img
              src="https://via.placeholder.com/400"
              alt="ここに本の画像"
              class="w-full rounded-lg shadow-md mt-3"
              />
              <div class="flex justify-between text-gray-500 mt-4 text-sm">
                <span class="cursor-pointer hover:text-blue-600">コメント 12</span>
                <span class="cursor-pointer hover:text-blue-600">いいね 89</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Post 2 -->
        <div class="bg-white shadow-md rounded-2xl p-4">
          <div class="flex gap-4">
            <img src="https://via.placeholder.com/50" alt="User Avatar" class="w-12 h-12 rounded-full" />
            <div class="w-full">
              <div class="flex justify-between items-center">
                <div>
                  <span class="inline-block bg-blue-100 text-blue-600 font-semibold px-2 py-1 rounded-full mt-2 mr-3">
                    本の感想
                  </span>
                  <span class="font-bold text-blue-600">山田太郎</span>
                  <span class="text-gray-500 text-sm ml-2">@taro_yamada</span>
                </div>
                <span class="text-gray-400 text-sm">1時間前</span>
              </div>
              <p class="text-gray-800 mt-2">ITエンジニアのための機械学習理論入門</p>
              <img
              src="https://via.placeholder.com/400"
              alt="ここに本の画像"
              class="w-full rounded-lg shadow-md mt-3"
              />
              <div class="flex justify-between text-gray-500 mt-4 text-sm">
                <span class="cursor-pointer hover:text-blue-600">コメント 12</span>
                <span class="cursor-pointer hover:text-blue-600">いいね 89</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Post 3 -->
        <div class="bg-white shadow-md rounded-2xl p-4">
          <div class="flex gap-4">
            <img src="https://via.placeholder.com/50" alt="User Avatar" class="w-12 h-12 rounded-full" />
            <div class="w-full">
              <div class="flex justify-between items-center">
                <div>
                  <span class="inline-block bg-blue-100 text-blue-600 font-semibold px-2 py-1 rounded-full mt-2 mr-3">
                    本の感想
                  </span>
                  <span class="font-bold text-blue-600">山田太郎</span>
                  <span class="text-gray-500 text-sm ml-2">@taro_yamada</span>
                </div>
                <span class="text-gray-400 text-sm">1時間前</span>
              </div>
              <p class="text-gray-800 mt-2">ITエンジニアのための機械学習理論入門</p>
              <img
              src="https://via.placeholder.com/400"
              alt="ここに本の画像"
              class="w-full rounded-lg shadow-md mt-3"
              />
              <div class="flex justify-between text-gray-500 mt-4 text-sm">
                <span class="cursor-pointer hover:text-blue-600">コメント 12</span>
                <span class="cursor-pointer hover:text-blue-600">いいね 89</span>
              </div>
            </div>
          </div>
        </div>







      </div>
    </div>
  </div>
</template>
