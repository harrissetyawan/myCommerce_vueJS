<script setup>
import Button from "./Atoms/Button.vue";
import SearchInput from "./Atoms/SearchInput.vue";
import Slider from "./Atoms/Slider.vue";

import {
  Bars3BottomLeftIcon,
  MagnifyingGlassIcon,
  UserIcon,
  ShoppingBagIcon,
  HeartIcon
} from "@heroicons/vue/24/outline"
import ButtonIco from "./Atoms/ButtonIco.vue";
import ButtonDropdown from "./Atoms/ButtonDropdown.vue";


const props = defineProps({
  promoMsg: String
});

</script>
<template>
  <div id="nav-top"
    class="h-7 w-full bg-fuchsia-950 flex items-center justify-center md:justify-between md:h-8 font-light text-sm border-b-[1px] border-b-slate-400 md:px-5">
    <!-- DropDown LANG Here -->
    <ButtonDropdown />
    <p class="text-center text-xs py-2">{{ promoMsg }}</p>
    <!-- Help & Informations -->
    <div class="flex flex-row gap-3">
      <a href="http://" class="hidden md:block hover:font-semibold">Help & Informations</a>
      <!-- Connect WIth Us -->
      <a href="http://" class="hidden md:block hover:font-semibold">Connect With Us</a>
    </div>
  </div>
  <nav class="w-full h-16 bg-fuchsia-950 flex flex-row justify-between items-center px-3 md:px-5">
    <div class="flex flex-row gap-3">
      <ButtonIco>
        <Bars3BottomLeftIcon class="h-8 w-8" />
      </ButtonIco>
      <ButtonIco>
        <MagnifyingGlassIcon class="h-5 w-5" />
      </ButtonIco>
    </div>
    <div class="flex flex-row gap-[0.6rem] pr-2">
      <ButtonIco>
        <UserIcon class="h-6 w-6" />
      </ButtonIco>
      <ButtonIco>
        <HeartIcon class="h-6 w-6" />
      </ButtonIco>
      <ButtonIco>
        <ShoppingBagIcon class="h-6 w-6" />
      </ButtonIco>
    </div>
  </nav>
  <SearchInput />
  <div class="h-11 w-full bg-pink-100 text-zinc-900 flex flex-row justify-center items-center">
    <p class="self-center font-bold tracking-wide">25% OFF - SITEWIDE -
      <span class="underline underline-offset-2 text-xs font-semibold inline-block align-middle tracking-tight">
        <a href="#">tap here</a>
      </span>
    </p>
  </div>
  <Slider />
</template>