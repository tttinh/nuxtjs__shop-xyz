<template>
  <div class="relative h-96 overflow-hidden">
    <img class="object-cover object-center w-full h-96" src="~/assets/images/shop-cover.png" alt="shop cover" />
    <div class="absolute bottom-0 w-full h-80 bg-gradient-to-t from-white"></div>
    <div class="absolute top-0 px-8 pt-24">
      <img class="w-20 h-20 rounded-full" src="~/assets/images/shop-avatar.png" alt="shop avatar" />
      <h1 class="pt-4 text-2xl font-bold line-clamp-2">{{ shop.name }}</h1>
      <p class="pt-2 text-xs line-clamp-2">{{ shop.desc }}</p>
      <p class="pt-4 text-xs">{{ shop.address }}</p>
      <p class="pt-4 text-xs">{{ shop.workingHours }}</p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    shop: {
      type: Object,
      required: true,
    },
  },
}
</script>
