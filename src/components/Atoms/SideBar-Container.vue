<script setup>
import {
  Bars3BottomLeftIcon,
  XMarkIcon,
  ChevronRightIcon,
  UserIcon,
  HeartIcon,
  ShoppingBagIcon
} from "@heroicons/vue/24/outline";

</script>
<template>
  <aside id="menu-bar" class="bg-slate-100 h-full w-3/4 float-left absolute top-0 drop-shadow-md">
    <div class="h-14 w-full bg-fuchsia-950 flex flex-row justify-between p-5 items-center">
      <Bars3BottomLeftIcon class="h-7 w-7" />
      <h1 class="text-slate-50 text-xl tracking-wide font-light">Menu</h1>
      <XMarkIcon class="h-7 w-7" />
    </div>
    <ul id="categories-list" class="px-5 text-slate-800 text-xl font-medium bg-white flex flex-col drop-shadow-sm">
      <li class="flex flex-row justify-between py-3 border-b-2 border-slate-300 items-center">
        <p class="">Fragrances</p>
        <ChevronRightIcon class="w-4 h-4" />
      </li>
      <li class="flex flex-row justify-between py-3 border-b-2 border-slate-300 items-center">
        <p class="">Skincare</p>
        <ChevronRightIcon class="w-4 h-4" />
      </li>
      <li class="flex flex-row justify-between py-3 border-b-2 border-slate-300 items-center">
        <p class="">Jewellery</p>
        <ChevronRightIcon class="w-4 h-4" />
      </li>
      <li class="flex flex-row justify-between py-3 border-b-2 border-slate-300 items-center">
        <p class="">Bags</p>
        <ChevronRightIcon class="w-4 h-4" />
      </li>
      <li class="flex flex-row justify-between py-3 items-center">
        <p class="">Dresses</p>
        <ChevronRightIcon class="w-4 h-4" />
      </li>
    </ul>
    <ul class="mt-4 px-5 text-slate-800 text-lg font-medium bg-white flex flex-col drop-shadow-sm">
      <li class="flex flex-row py-3 items-center justify-between border-b-2 border-slate-300">
        <div class="flex flex-row">
          <UserIcon class="w-6 h-6 mr-3" />
          <p class="">My Account</p>
        </div>
        <ChevronRightIcon class="w-4 h-4" />

      </li>
      <li class="flex flex-row py-3 items-center justify-between border-b-2 border-slate-300">
        <div class="flex flex-row">
          <HeartIcon class="w-6 h-6 mr-3" />
          <p class="">Wishlist <span>(0)</span></p>
        </div>
        <ChevronRightIcon class="w-4 h-4" />

      </li>
      <li class="flex flex-row py-3 items-center justify-between">
        <div class="flex flex-row">
          <ShoppingBagIcon class="w-6 h-6 mr-3" />
          <p class=""><span>2</span> Items</p>
        </div>
        <ChevronRightIcon class="w-4 h-4" />
      </li>
    </ul>

    <ul class="mt-9 px-5">
      <li class="py-3">
        <h3 class="text-zinc-600 underline text-lg underline-offset-2 tracking-tight ">
          Currency: <span class="pl-">USD</span>
        </h3>
      </li>
      <li class="py-3">
        <h3 class="text-zinc-600 underline text-lg underline-offset-2 tracking-tight ">
          Language: <span class="pl-">English</span>
        </h3>
      </li>
      <li class="py-3">
        <h3 class="text-zinc-600 underline text-lg underline-offset-2 tracking-tight ">
          Help & Informations
        </h3>
      </li>
    </ul>
  </aside>
</template>