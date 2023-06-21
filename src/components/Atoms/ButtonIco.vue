<script setup>
import {
  Bars3BottomLeftIcon,
  MagnifyingGlassIcon,
  UserIcon,
  ShoppingBagIcon,
  HeartIcon,
  ChevronRightIcon,
  ChevronLeftIcon
} from "@heroicons/vue/24/outline"

const props = defineProps({
  className: {
    type: String,
    default: ''
  }
})
</script>
<template>
  <button :class="className">
    <slot>
    </slot>
  </button>
</template>