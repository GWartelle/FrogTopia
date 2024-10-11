<script setup>
import frog2 from "@/assets/DALL_E_Frog2.png";
import vector2 from "@/assets/vector-background-2.svg";
</script>

<template>
  <section id="promo" class="py-20 bg-secondary flex justify-center shadow-md">
    <div class="flex gap-20 items-center flex-col lg:flex-row">
      <div class="flex flex-col items-center gap-10 max-w-96">
        <h2
          class="font-extrabold text-4xl bg-gradient-to-r from-primary to-accent text-transparent bg-clip-text"
        >
          Frog of the month
        </h2>
        <p class="text-center font-bold text-xl px-5">
          The Lilaeana Purpurea won this month competition ! <br />
          Don't miss out on this beautiful companion 🐸
        </p>
        <button
          class="btn border-none bg-primary text-light hover:bg-accent font-bold text-xl shadow-md"
        >
          Get it for -20%
        </button>
      </div>
      <div class="relative">
        <img
          :src="frog2"
          alt="gentle purple frog"
          class="absolute h-72 w-72 left-20 bottom-0 z-50 filter drop-shadow-2xl"
        />
        <img
          :src="vector2"
          alt="vector background"
          class="h-64 filter drop-shadow-2xl"
        />
      </div>
    </div>
  </section>
</template>
