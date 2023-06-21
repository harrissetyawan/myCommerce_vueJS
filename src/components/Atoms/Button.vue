<script setup>
const props = defineProps({
  textBtn: String
})
</script>

<template>
  <button
    class="px-5 py-1 bg-fuchsia-950 font-semibold border-l-purple-300 shadow-gray-900 hover:opacity-80 tracking-tight text-sm">
    {{ textBtn }}
  </button>
</template>