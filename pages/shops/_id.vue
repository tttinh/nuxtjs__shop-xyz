<template>
  <shop :shop="shop" />
</template>

<script>
export default {
  data() {
    return {
      shop: {
        cover: '',
        avatar: '',
        name: 'Lorem ipsum dolor sit amet consectetur adipisicing elit.',
        desc: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Rem, eligendi. Autem dicta distinctio dolore totam saepe. Perferendis repellendus nisi, cum quod veniam, corporis vitae animi eveniet nostrum sapiente eum nihil.',
        address: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi, fuga.',
        workingHours: 'Everyday everytime',
      },
    }
  },
}
</script>
