<script setup>

const langs = [
  { label: "ENG", value: "english" },
  { label: "ID", value: "indonesian" },
]
</script>

<template>
  <select id="cars" class="text-gray-50 border-none bg-transparent text-sm focus:outline-none hidden md:block">
    <option class="bg-black" value="EN">English</option>
    <option class="bg-black" value="ID">Indonesia</option>
  </select>
</template>
