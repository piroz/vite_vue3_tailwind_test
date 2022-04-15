<script setup>

import { event } from "vue-gtag"

const onSignupClick = (e) => {
  event('outbound', {
    'event_category': 'https://forms.gle/AnYcfBBdU3bXwY3e6',
    'event_label': 'bottom',
  })
}
</script>

<template>
<section class="text-gray-600 body-font">
  <div class="container px-5 py-12 mx-auto">
    <div class="xl:w-1/2 lg:w-3/4 w-full mx-auto">
      <h2 class="leading-relaxed text-4xl font-extrabold">残りの個数はStockedで確認</h2>
      <span class="inline-block h-1 w-10 rounded bg-indigo-500 mt-8 mb-6"></span>
      <ul class="list-none text-gray-900 font-medium title-font tracking-wider leading-relaxed text-xl">
        <li class="">1. まず数えたいモノを写真で撮影します</li>
        <li class="">2. モノの個数をStockedが自動で数えあげ登録します</li>
        <li class="">3. 残りの個数はいつでもStockedで確認できます</li>
      </ul>
    </div>
  </div>
</section>
<section class="text-gray-600 body-font overflow-hidden">
  <div class="container px-5 py-12 mx-auto">
    <div class="flex flex-wrap -m-4">
      <div class="p-4 xl:w-1/3 md:w-1/2 w-full">
        <div class="h-full p-6 rounded-lg border-2 border-gray-300 flex flex-col relative overflow-hidden">
          <h2 class="text-sm tracking-widest title-font mb-1 font-medium">START</h2>
          <h1 class="text-5xl text-gray-900 pb-4 mb-4 border-b border-gray-200 leading-none">Free</h1>
          <p class="flex items-center text-gray-600 mb-2">
            <span class="w-4 h-4 mr-2 inline-flex items-center justify-center bg-gray-400 text-white rounded-full flex-shrink-0">
              <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" class="w-3 h-3" viewBox="0 0 24 24">
                <path d="M20 6L9 17l-5-5"></path>
              </svg>
            </span>登録数1
          </p>
        </div>
      </div>
      <div class="p-4 xl:w-1/3 md:w-1/2 w-full">
        <div class="h-full p-6 rounded-lg border-2 border-gray-300 flex flex-col relative overflow-hidden">
          <h2 class="text-sm tracking-widest title-font mb-1 font-medium">STANDARD</h2>
          <h1 class="text-5xl text-gray-900 leading-none flex items-center pb-4 mb-4 border-b border-gray-200">
            <span>500円</span>
            <span class="text-lg ml-1 font-normal text-gray-500">/月</span>
          </h1>
          <p class="flex items-center text-gray-600 mb-2">
            <span class="w-4 h-4 mr-2 inline-flex items-center justify-center bg-gray-400 text-white rounded-full flex-shrink-0">
              <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" class="w-3 h-3" viewBox="0 0 24 24">
                <path d="M20 6L9 17l-5-5"></path>
              </svg>
            </span>登録数5
          </p>
        </div>
      </div>
      <div class="p-4 xl:w-1/3 md:w-1/2 w-full">
        <div class="h-full p-6 rounded-lg border-2 border-gray-300 flex flex-col relative overflow-hidden">
          <h2 class="text-sm tracking-widest title-font mb-1 font-medium">PRO</h2>
          <h1 class="text-5xl text-gray-900 leading-none flex items-center pb-4 mb-4 border-b border-gray-200">
            <span>1990円</span>
            <span class="text-lg ml-1 font-normal text-gray-500">/月</span>
          </h1>
          <p class="flex items-center text-gray-600 mb-2">
            <span class="w-4 h-4 mr-2 inline-flex items-center justify-center bg-gray-400 text-white rounded-full flex-shrink-0">
              <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" class="w-3 h-3" viewBox="0 0 24 24">
                <path d="M20 6L9 17l-5-5"></path>
              </svg>
            </span>登録数30
          </p>
        </div>
      </div>
    </div>
  </div>
</section>
<section class="text-gray-600 body-font">
  <div class="container px-5 py-24 mx-auto">
    <div class="lg:w-2/3 flex flex-col sm:flex-row sm:items-center items-start mx-auto">
      <p class="flex-grow sm:pr-16 text-2xl font-medium title-font text-gray-900">Stockedはリリースの準備段階です。事前登録ユーザには利用ができるようになったときに通知をさせていただきます。</p>
      <a href="https://forms.gle/AnYcfBBdU3bXwY3e6" @click="onSignupClick" target="_blank" rel="noopener noreferrer" class="flex-shrink-0 text-white bg-indigo-500 border-0 py-2 px-8 focus:outline-none hover:bg-indigo-600 rounded text-lg mt-10 sm:mt-0">事前登録する</a>
    </div>
  </div>
</section>
</template>
