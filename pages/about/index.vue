<script setup lang="ts">
definePageMeta({
    layout: 'dashboard' // Assuming 'dashboard' is your layout for this page
})
</script>

<template>
  <div class="about-page p-4">
    <h1 class="text-3xl font-bold text-center mb-4">About Us</h1>
    <p class="text-lg text-gray-700 leading-relaxed text-justify max-w-3xl mx-auto">
      Welcome to our website! We are committed to providing the best services and solutions for our community.
      Our goal is to create a platform that brings together innovation, collaboration, and excellence. 
    </p>

    <div class="mt-6">
      <h2 class="text-2xl font-semibold text-gray-800 mb-2">Our Mission</h2>
      <p class="text-gray-700">
        To empower individuals and organizations by delivering top-notch solutions and fostering a vibrant community.
      </p>
    </div>

    <div class="mt-6">
      <h2 class="text-2xl font-semibold text-gray-800 mb-2">Our Vision</h2>
      <p class="text-gray-700">
        To be a leading force in innovation and community-driven initiatives, setting a standard for excellence and integrity.
      </p>
    </div>
  </div>
</template>

<style scoped>
.about-page {
  background-color: #f9f9f9; /* Light background */
  border-radius: 8px;       /* Rounded corners */
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Subtle shadow */
}
</style>
