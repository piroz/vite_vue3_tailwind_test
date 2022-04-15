<script setup>

</script>

<template>
  <div>
    <header class="bg-white shadow" v-if="$route.meta.title">
      <div class="px-4 py-6 mx-auto max-w-7xl sm:px-6 lg:px-8">
        <h1
          class="text-3xl font-bold leading-tight text-gray-900"
        >
        Stocked
        </h1>
      </div>
    </header>
    <main>
      <router-view />
    </main>
    <footer class="text-gray-600 body-font">
      <div class="bg-gray-100">
        <div class="container mx-auto py-4 px-5 flex flex-wrap flex-col sm:flex-row">
          <p class="text-gray-500 text-sm text-center sm:text-left">Stocked by Qualtec</p>
        </div>
      </div>
    </footer>
  </div>
</template>
