<script setup>
import frog2 from "@/assets/DALL_E_Frog2.png";
import vector2 from "@/assets/vector-background-2.svg";
</script>

<template>
  <section class="h-auto py-24 bg-secondary flex justify-center shadow-md">
    <div class="flex gap-12 items-center">
      <div class="flex flex-col items-center gap-6 max-w-96">
        <h2
          class="font-extrabold text-3xl bg-gradient-to-r from-primary to-accent text-transparent bg-clip-text"
        >
          Frog of the month
        </h2>
        <p class="text-center font-bold text-xl">
          The Lilaeana Purpurea won this month competition ! <br />
          Don't miss out on this beautiful companion 🐸
        </p>
        <button
          class="btn border-none bg-gradient-to-r from-primary to-accent text-light font-bold text-xl shadow-md"
        >
          Get it for -20%
        </button>
      </div>
      <div class="relative">
        <img
          :src="frog2"
          alt="gentle purple frog"
          class="absolute h-72 left-20 bottom-1"
        />
        <img :src="vector2" alt="vector backaground" class="h-64" />
      </div>
    </div>
  </section>
</template>
