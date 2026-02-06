<template>
  <section class="relative bg-gradient-to-b from-[#42389E] to-[#0F1026] overflow-hidden pt-24 pb-16 md:pt-32 md:pb-24">
    <!-- Decorative Background Element -->
    <div class="absolute bottom-0 right-0 w-1/2 h-64 bg-primary-dark rounded-tl-[100px] opacity-50"></div>
    
    <div class="container mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
      <div class="max-w-4xl mx-auto text-center">
        <!-- Main Heading -->
        <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-white mb-6">
          The First 
          <span class="bg-accent-yellow text-primary px-3 py-1 rounded inline-block">Dart-Native</span>
          Feature Flag<br class="hidden md:block" />
          With DartCodeAI
        </h1>

        <!-- Subheading -->
        <p class="text-lg md:text-xl text-white/90 mb-8 max-w-2xl mx-auto">
          Feature flags built for Dart, Ship faster, roll back<br />
          safely, and scale with AI-powered delivery<br />
          Starting at just $1/month
        </p>

        <!-- CTA Buttons -->
        <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-12">
          <button class="bg-accent-orange hover:bg-orange-500 text-white px-8 py-3 rounded-md font-semibold transition-colors w-full sm:w-auto">
            Get Access
          </button>
          <button class="border-2 border-white text-white hover:bg-white hover:text-primary px-8 py-3 rounded-md font-semibold transition-colors w-full sm:w-auto">
            Join AI Early Access
          </button>
        </div>

        <!-- Dashboard Preview -->
        <div class="relative max-w-5xl mx-auto">
          <!-- PNG Frame from Figma -->
          <div class="relative inline-block w-full">
            <img 
              src="public/images/dashboardFrame.png" 
              alt="Dashboard Frame" 
              class="w-full"
            />
            
            <!-- GIF positioned inside - NO HEIGHT, just width -->
            <div class="absolute top-[10%] left-[5%] right-[5%]">
              <img 
                src="public/images/dashboard.png" 
                alt="Dashboard Demo" 
                class="w-full"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
