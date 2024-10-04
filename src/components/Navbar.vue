<script setup>
import logo from "@/assets/frog-logo.svg";
</script>

<template>
  <header
    class="bg-light bg-opacity-60 backdrop-blur-lg px-5 py-2 flex justify-between border-b border-dark border-opacity-25 fixed top-0 right-0 left-0 shadow-lg"
  >
    <a href="#" class="flex gap-5 items-center">
      <img :src="logo" class="w-10" />
      <span
        class="font-extrabold text-3xl bg-gradient-to-r from-primary to-accent text-transparent bg-clip-text"
        >FrogTopia</span
      >
    </a>
    <nav class="flex gap-10 items-center">
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
    </nav>
  </header>
</template>
