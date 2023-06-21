<script setup>
import ButtonIco from './ButtonIco.vue';
import {
  ChevronLeftIcon,
  ChevronRightIcon
} from "@heroicons/vue/24/outline"
</script>
<template>
  <div class="h-60 w-full mt-5 bg-zinc-200 ">
    <ButtonIco className="bg-zinc-600 w-3 h-3">
      <ChevronLeftIcon class="w-3 h-3 text-black stroke-[4]" />
    </ButtonIco>
  </div>
</template>