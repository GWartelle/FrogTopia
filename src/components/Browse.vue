<script setup>
import Card from "./Card.vue";
import blueFrog from "../assets/frogs/blue-frog.jpg";
import greenFrog from "../assets/frogs/green-frog.jpg";
import orangeFrog from "../assets/frogs/orange-frog.jpg";
import redFrog from "../assets/frogs/red-frog.jpg";
import whiteFrog from "../assets/frogs/white-frog.jpg";
import yellowFrog from "../assets/frogs/yellow-frog.jpg";

const frogsData = [
  {
    image: blueFrog,
    title: "Leptopelis Caeruleus",
    text: "This elusive blue leaf frog prefers high-altitude tropical forests, where it hides among leaves. Its soft croaks are a familiar nighttime sound in the forest.",
    price: 190,
  },
  {
    image: greenFrog,
    title: "Rana Viridisca",
    text: "A bright green river-dwelling frog, often found near fast-flowing streams. Its smooth skin and excellent camouflage make it a master at avoiding predators.",
    price: 310,
  },
  {
    image: orangeFrog,
    title: "Hyla Aurantiaca",
    text: "A vibrant orange tree frog found in the rainforest canopy. Known for its striking color and ability to blend with sunlit leaves, it uses its large toe pads to cling to branches.",
    price: 245,
  },
  {
    image: redFrog,
    title: "Rana Rubripura",
    text: "This striking red frog inhabits riverbanks and streams in tropical rainforests. Its smooth, vivid red skin helps it stand out during mating season, while it blends seamlessly into its red clay habitat for protection.",
    price: 275,
  },
  {
    image: whiteFrog,
    title: "Leptodactylus Alba",
    text: "A small, cream-colored frog with silky skin, commonly found in leaf litter on the rainforest floor. Its pale hue provides excellent camouflage against sandy or light-colored soil, making it difficult for predators to spot.",
    price: 165,
  },
  {
    image: yellowFrog,
    title: "Hyla Flavoluna",
    text: "A bright yellow tree frog often seen at night in the rainforest canopy. Its smooth, luminous skin reflects the moonlight, giving it a glowing appearance as it calls for mates high in the treetops.",
    price: 360,
  },
];
</script>

<template>
  <section class="flex justify-center">
    <div class="max-w-4xl flex flex-col items-center gap-10 py-10">
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
      <div class="flex flex-wrap justify-center gap-5">
        <Card
          v-for="(frog, index) in frogsData"
          :key="index"
          :image="frog.image"
          :title="frog.title"
          :text="frog.text"
          :price="frog.price"
        />
      </div>
      <div class="join shadow-md">
        <button class="join-item btn btn-disabled">«</button>
        <button class="join-item btn btn-active">1</button>
        <button class="join-item btn">2</button>
        <button class="join-item btn">3</button>
        <button class="join-item btn">»</button>
      </div>
    </div>
  </section>
</template>
