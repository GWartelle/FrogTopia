<script setup>
defineProps({
  image: {
    type: String,
    required: true,
  },
  title: {
    type: String,
    required: true,
  },
  text: {
    type: String,
    required: true,
  },
  price: {
    type: Number,
    required: true,
  },
});
</script>

<template>
  <div
    class="bg-secondary rounded-lg shadow-md max-w-sm flex flex-col items-center gap-3 px-3 py-5"
  >
    <img
      :src="image"
      :alt="title"
      class="h-44 w-44 object-cover rounded-lg shadow-lg"
    />
    <h3 class="text-dark font-bold text-xl">{{ title }}</h3>
    <p class="text-dark text-center">{{ text }}</p>
    <span class="text-dark font-bold text-2xl">${{ price }}</span>
    <div class="flex gap-5">
      <button
        class="btn border-none bg-primary text-light hover:bg-accent font-bold text-lg shadow-md"
      >
        Read more
      </button>
      <button
        class="btn border-none bg-primary text-light hover:bg-accent font-bold text-lg shadow-md"
      >
        Add to cart
      </button>
    </div>
  </div>
</template>
