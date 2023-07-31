<template>
  <div class="px-2 py-2 font-medium text-end">
    <div class="text-red-400 cursor-pointer" @click="openLink">@keilanerizza</div>
    <div class="text-slate-500">Bodybuilder</div>
  </div>
  <img  class="sm:w-30 md:w-30 w-full" quality="100" src="./public/keilane.jpg" />

</template>

<script setup>
function openLink() {
  window.open('https://linktr.ee/keilanerizza')
}
// const { locale } = useI18n()
// locale.value = window.navigator.language.split('-')[0];
</script>

<style>
body {
  background: linear-gradient(45deg, black, #090905);
}

img {
  z-index: -2;
}
</style>