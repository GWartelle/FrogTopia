<script setup>
import logo from "@/assets/frog-logo.svg";
</script>

<template>
  <header
    class="bg-light bg-opacity-60 backdrop-blur-lg px-5 py-2 flex justify-between border-b border-dark border-opacity-25 fixed top-0 right-0 left-0 shadow-lg z-50"
  >
    <!-- Logo section -->
    <a href="#" class="flex gap-5 items-center">
      <img :src="logo" class="w-10" />
      <span
        class="font-extrabold text-3xl bg-gradient-to-r from-primary to-accent text-transparent bg-clip-text"
        >FrogTopia</span
      >
    </a>

    <!-- Desktop navigation links -->
    <nav class="hidden lg:flex gap-10 items-center">
      <a href="#hero" class="font-bold text-xl"> Home </a>
      <a href="#promo" class="font-bold text-xl"> Deal </a>
      <a href="#browse" class="font-bold text-xl"> Browse </a>
      <a href="#reviews" class="font-bold text-xl"> Reviews </a>
      <a href="#">
        <button
          class="btn border-none bg-primary text-light hover:bg-accent font-bold text-xl shadow-md px-6"
        >
          Login
        </button>
      </a>
    </nav>

    <!-- Mobile navigation dropdown -->
    <div class="dropdown dropdown-end lg:hidden">
      <button tabindex="0">
        <v-icon name="hi-solid-menu" scale="2" fill="#002A19" />
      </button>
      <ul
        tabindex="0"
        class="dropdown-content menu bg-base-100 rounded-box z-50 w-52 p-2 shadow"
      >
        <li><a href="#hero" class="font-bold text-xl">Home</a></li>
        <li><a href="#promo" class="font-bold text-xl">Deal</a></li>
        <li><a href="#browse" class="font-bold text-xl">Browse</a></li>
        <li><a href="#reviews" class="font-bold text-xl">Reviews</a></li>
        <li>
          <a href="#">
            <button
              class="btn border-none bg-primary text-light hover:bg-accent font-bold text-xl shadow-md w-full"
            >
              Login
            </button>
          </a>
        </li>
      </ul>
    </div>
  </header>
</template>
