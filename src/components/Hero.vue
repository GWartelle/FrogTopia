<script setup>
import frog1 from "@/assets/DALL_E_Frog1.png";
import vector1 from "@/assets/vector-background-1.svg";
</script>

<template>
  <section class="pt-24 h-screen flex justify-center">
    <div class="flex gap-12 items-center">
      <div class="flex flex-col justify-center items-center gap-10">
        <h1
          class="font-extrabold text-3xl bg-gradient-to-r from-primary to-accent text-transparent bg-clip-text"
        >
          FULFILL YOUR DREAM<br />GET A FROG
        </h1>
        <button
          class="btn btn-lg px-10 border-none bg-primary text-light hover:bg-accent font-bold text-xl shadow-md"
        >
          Browse Frogs
        </button>
      </div>
      <div class="relative">
        <img
          :src="frog1"
          alt="beautidul blue frog"
          class="w-96 absolute right-14 bottom-14"
        />
        <img :src="vector1" alt="vector background" class="w-96" />
      </div>
    </div>
  </section>
</template>
