<template>
  <div class="space-y-10 mb-20">
    <!-- Header -->
    <div class="w-full flex justify-center px-2 md:px-0 py-4 bg-green-700">
      <!-- Group 1 -->
      <div class="max-w-screen-lg justify-between flex space-x-4 items-center w-full">

        <div>
          <img class="h-10" src="https://www.lapor.go.id/themes/lapor/assets/images/logo-white.png" alt="">
        </div>
        <div class="hidden md:flex space-x-4 font-medium text-slate-100">
          <p>Tentang Lapor</p>
          <p>Statistik</p>
        </div>
        <div class="hidden md:block">
          <button class="px-4 py-2 flex space-x-2 bg-slate-800 text-white rounded-full">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"  class="icon icon-tabler icons-tabler-outline icon-tabler-route-2"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M3 19a2 2 0 1 0 4 0a2 2 0 0 0 -4 0" /><path d="M19 7a2 2 0 1 0 0 -4a2 2 0 0 0 0 4z" /><path d="M14 5a2 2 0 0 0 -2 2v10a2 2 0 0 1 -2 2" /></svg>
            <p>LACAK</p>
          </button>
        </div>

        <div>
          <button>
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="h-8 w-8"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M4 6l16 0" /><path d="M4 12l16 0" /><path d="M4 18l16 0" /></svg>
          </button>
        </div>
      </div>
    </div>
    <!-- Header -->
    <div class="max-w-screen-lg px-2 md:px-0 mx-auto justify-center w-full">
      <slot />
    </div>
    <!-- <AppFooter /> -->
  </div>
</template>
