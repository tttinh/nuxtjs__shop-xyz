<template>
  <div>
    <shop-info :shop="shop" />
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
