<template>
  <header class="fixed top-0 left-0 right-0 bg-primary z-50">
    <nav class="container mx-auto px-4 sm:px-6 lg:px-8 py-4">
      <div class="flex items-center justify-between">
        <!-- Logo -->
        <div class="flex items-center space-x-2">
          <img src="/public/images/logo.svg" alt="IntelliToggle Logo" class="h-8" />
          <span class="text-white font-semibold text-lg">IntelliToggle</span>
        </div>

        <!-- Desktop Navigation -->
        <div class="hidden md:flex items-center space-x-8">
          <a href="#" class="text-white hover:text-accent-orange transition-colors">Home</a>
          <a href="#" class="text-white hover:text-accent-orange transition-colors">About</a>
          <a href="#" class="text-white hover:text-accent-orange transition-colors">Pricing</a>
        </div>

        <!-- CTA Button -->
        <div class="hidden md:block">
          <button class="bg-accent-orange hover:bg-orange-500 text-white px-6 py-2 rounded-md font-semibold transition-colors">
            Start Sandbox
          </button>
        </div>

        <!-- Mobile Menu Button -->
        <button 
          @click="toggleMenu" 
          class="md:hidden text-white p-2"
          aria-label="Toggle menu"
        >
          <svg v-if="!isMenuOpen" class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
          </svg>
          <svg v-else class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
          </svg>
        </button>
      </div>

      <!-- Mobile Menu -->
      <div v-if="isMenuOpen" class="md:hidden mt-4 pb-4 space-y-4">
        <a href="#" class="block text-white hover:text-accent-orange transition-colors">Home</a>
        <a href="#" class="block text-white hover:text-accent-orange transition-colors">Use Cases</a>
        <a href="#" class="block text-white hover:text-accent-orange transition-colors">Pricing</a>
        <button class="w-full bg-accent-orange hover:bg-orange-500 text-white px-6 py-2 rounded-md font-semibold transition-colors">
          Get a Demo
        </button>
      </div>
    </nav>
  </header>
</template>

<script setup>
const isMenuOpen = ref(false)

const toggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value
}
</script>
