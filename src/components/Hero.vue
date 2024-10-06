<script setup>
import frog from "@/assets/DALL_E_Frog1.png";
import vector from "@/assets/vector-background-1.svg";
</script>

<template>
  <section class="pt-24 flex justify-center">
    <div class="flex gap-10">
      <div class="flex flex-col justify-center items-center gap-10">
        <h1
          class="font-extrabold text-3xl bg-gradient-to-r from-primary to-accent text-transparent bg-clip-text"
        >
          FULFILL YOUR DREAM<br />GET A FROG
        </h1>
        <button
          class="btn bg-gradient-to-r from-primary to-accent text-light font-bold text-xl"
        >
          Browse Frogs
        </button>
      </div>
      <div class="relative">
        <img
          :src="frog"
          alt="beautidul blue frog"
          class="w-96 absolute right-14 bottom-14"
        />
        <img :src="vector" alt="vector background" class="w-96" />
      </div>
    </div>
  </section>
</template>
