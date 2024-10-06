<script setup>
import Card from "./Card.vue";
import frog from "../assets/frogs/blue-frog.jpg";

const alt = "This is a frog";
const title = "THIS IS A BLUE FROG";
const text = "THIS BLUE FROG IS BLUE";
const price = 999.99;
</script>

<template>
  <section class="flex flex-col items-center gap-10 py-10">
    <h2
      class="font-extrabold text-3xl bg-gradient-to-r from-primary to-accent text-transparent bg-clip-text"
    >
      Browse Frogs
    </h2>
    <label
      class="input input-bordered flex items-center gap-2 rounded-full border-dark"
    >
      <input type="text" class="grow" placeholder="Search for a frog..." />
      <v-icon name="hi-search" fill="#002A19" />
    </label>
    <Card
      class="bg-secondary rounded-lg shadow-md"
      :image="frog"
      :alt="alt"
      :title="title"
      :text="text"
      :price="price"
    />
  </section>
</template>
