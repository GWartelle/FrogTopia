<script setup>
import logo from "@/assets/frog-logo.svg";
</script>

<template>
  <nav class="flex px-5 py-2 justify-between border-b border-dark">
    <a href="#" class="flex gap-5 items-center">
      <img :src="logo" class="w-10" />
      <span
        class="font-extrabold text-3xl bg-gradient-to-r from-primary to-accent text-transparent bg-clip-text"
        >FrogTopia</span
      >
    </a>
    <div class="flex gap-10 items-center">
      <a href="#" class="font-bold text-xl"> Home </a>
      <a href="#" class="font-bold text-xl"> Deal </a>
      <a href="#" class="font-bold text-xl"> Browse </a>
      <a href="#" class="font-bold text-xl"> Reviews </a>
      <a href="#">
        <button
          class="btn bg-gradient-to-r from-primary to-accent text-light font-bold text-xl"
        >
          Login
        </button>
      </a>
    </div>
  </nav>
</template>
