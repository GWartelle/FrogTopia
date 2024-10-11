<script setup></script>

<template>
  <section
    id="reviews"
    class="h-auto mb-10 bg-secondary flex justify-center shadow-md"
  >
    <div class="max-w-4xl flex flex-col items-center gap-5 py-10 px-5">
      <h2
        class="text-center font-extrabold text-4xl bg-gradient-to-r from-primary to-accent text-transparent bg-clip-text"
      >
        Thinking about getting a frog? <br />
        Let our happy customers convince you!
      </h2>
      <h3 class="font-bold text-dark">D. Evans</h3>
      <p class="text-center italic text-dark">
        “I recently added a Leptopelis caeruleus to my collection, and I’m
        absolutely thrilled! The vibrant blue coloration is even more striking
        in person, and it really stands out in my rainforest-themed terrarium.
        The frog is quite active at night, and I love watching it gracefully
        climb through the plants with its large toe pads. It’s a bit shy during
        the day but comes alive when the lights go down, making evening
        observation a real treat.<br /><br />
        Caring for it has been easier than I expected—just the right amount of
        humidity and some well-placed plants to mimic its natural habitat. The
        best part? Its soft, gentle croaks create a calming atmosphere in the
        room. Definitely a unique and fascinating pet for anyone who loves
        amphibians!”
      </p>
      <div class="flex flex-col gap-5 items-center">
        <div class="form-control flex flex-row gap-5">
          <input
            type="radio"
            name="reviews"
            class="radio radio-sm checked:bg-dark"
            checked="checked"
          />
          <input
            type="radio"
            name="reviews"
            class="radio radio-sm checked:bg-dark"
          />
          <input
            type="radio"
            name="reviews"
            class="radio radio-sm checked:bg-dark"
          />
        </div>
        <progress class="progress w-11/12" value="40" max="100"></progress>
      </div>
    </div>
  </section>
</template>
