<script setup>
import frog1 from "@/assets/DALL_E_Frog1.png";
import vector1 from "@/assets/vector-background-1.svg";
</script>

<template>
  <section id="hero" class="lg:h-screen py-20 flex justify-center">
    <div class="flex gap-28 items-center flex-col lg:flex-row">
      <div class="flex flex-col justify-center items-center gap-24">
        <h1
          class="font-extrabold text-5xl bg-gradient-to-r from-primary to-accent text-transparent bg-clip-text text-center lg:text-left"
        >
          FULFILL YOUR DREAM<br />GET A FROG
        </h1>
        <a
          href="#browse"
          class="btn btn-lg px-10 border-none bg-primary text-light hover:bg-accent font-bold text-xl shadow-md"
        >
          Browse Frogs
        </a>
      </div>
      <div class="relative">
        <img
          :src="frog1"
          alt="beautidul blue frog"
          class="absolute right-14 bottom-14"
        />
        <img :src="vector1" alt="vector background" class="" />
      </div>
    </div>
  </section>
</template>
