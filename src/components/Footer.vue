<script setup></script>
<template>
  <footer class="px-5 py-2 border-t border-dark border-opacity-25 shadow-lg">
    <div class="relative flex justify-end items-center">
      <!-- Links for large screens -->
      <div
        class="hidden lg:flex absolute left-1/2 transform -translate-x-1/2 gap-20"
      >
        <a href="#" class="font-bold text-xl"> About us </a>
        <a href="#" class="font-bold text-xl"> Policies </a>
        <a href="#" class="font-bold text-xl"> Contact us </a>
      </div>

      <!-- Dropdown for small screens -->
      <div
        class="lg:hidden dropdown dropdown-top absolute left-1/2 transform -translate-x-1/2"
      >
        <button tabindex="0" class="font-bold text-xl">More</button>
        <ul
          tabindex="0"
          class="dropdown-content menu bg-base-100 rounded-box z-50 w-52 p-2 shadow"
        >
          <li><a href="#" class="font-bold text-xl">About us</a></li>
          <li><a href="#" class="font-bold text-xl">Policies</a></li>
          <li><a href="#" class="font-bold text-xl">Contact us</a></li>
        </ul>
      </div>

      <!-- Back to top link -->
      <a href="#hero" class="font-bold text-xl"> Back to top </a>
    </div>
  </footer>
</template>
