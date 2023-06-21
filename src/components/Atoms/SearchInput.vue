<script setup>
import Button from './Button.vue';
const props = defineProps({
  placeholder: String
})
</script>

<template>
  <div class="bg-white h-fit w-full outline outline-2 outline-fuchsia-900 flex flex-row p-1">
    <input type="text" name="search-input" id="search-input"
      class="py-2 px-2 w-full text-sm text-zinc-900 focus:outline-none" placeholder="Hey, What're you looking for ?">
    <Button text-btn="SEARCH" />
  </div>
</template>