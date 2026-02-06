<template>
  <section class="relative bg-primary overflow-hidden pt-24 pb-16 md:pt-32 md:pb-24">
    <!-- Decorative Background Element -->
    <div class="absolute bottom-0 right-0 w-1/2 h-64 bg-primary-dark rounded-tl-[100px] opacity-50"></div>
    
    <div class="container mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
      <div class="max-w-4xl mx-auto text-center">
        <!-- Badges -->
        <div class="flex items-center justify-center gap-3 mb-6">
          <span class="bg-accent-yellow text-primary px-4 py-1 rounded-full text-sm font-semibold">
            Dart & Node.js
          </span>
        </div>

        <!-- Main Heading -->
        <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-white mb-6">
          The First 
          <span class="bg-accent-yellow text-primary px-3 py-1 rounded inline-block">Dart & Node</span>
          Feature Flag<br class="hidden md:block" />
          With DartCodeAI
        </h1>

        <!-- Subheading -->
        <p class="text-lg md:text-xl text-white/90 mb-8 max-w-2xl mx-auto">
          Feature Flag Control Panel for Feature Releases<br />
          Simple. Easy. Fast. Start your 7-day free trial today!
        </p>

        <!-- CTA Buttons -->
        <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-12">
          <button class="bg-accent-orange hover:bg-orange-500 text-white px-8 py-3 rounded-md font-semibold transition-colors w-full sm:w-auto">
            Get Started Free
          </button>
          <button class="border-2 border-white text-white hover:bg-white hover:text-primary px-8 py-3 rounded-md font-semibold transition-colors w-full sm:w-auto">
            Get Started Now →
          </button>
        </div>

        <!-- Dashboard Preview -->
        <div class="relative max-w-5xl mx-auto">
          <div class="bg-white rounded-lg shadow-2xl overflow-hidden">
            <!-- Browser Chrome -->
            <div class="bg-gray-800 px-4 py-3 flex items-center gap-2">
              <div class="flex gap-2">
                <div class="w-3 h-3 rounded-full bg-red-500"></div>
                <div class="w-3 h-3 rounded-full bg-yellow-500"></div>
                <div class="w-3 h-3 rounded-full bg-green-500"></div>
              </div>
              <div class="flex-1 bg-gray-700 rounded px-4 py-1 text-xs text-gray-300">
                dashboard.intellitoggle.com
              </div>
            </div>
            
            <!-- Dashboard Content -->
            <div class="bg-gray-50 p-6">
              <div class="bg-white rounded shadow-sm p-4 mb-4">
                <div class="flex items-center justify-between mb-4">
                  <h3 class="font-semibold text-gray-800">Feature Flags</h3>
                  <button class="bg-primary text-white px-4 py-2 rounded text-sm">+ New Flag</button>
                </div>
                <div class="space-y-2">
                  <div class="flex items-center justify-between py-3 border-b">
                    <div class="flex items-center gap-4">
                      <div class="w-10 h-6 bg-green-500 rounded-full relative">
                        <div class="absolute right-1 top-1 w-4 h-4 bg-white rounded-full"></div>
                      </div>
                      <span class="text-sm">new-checkout-flow</span>
                    </div>
                    <span class="text-xs text-gray-500">100%</span>
                  </div>
                  <div class="flex items-center justify-between py-3 border-b">
                    <div class="flex items-center gap-4">
                      <div class="w-10 h-6 bg-gray-300 rounded-full relative">
                        <div class="absolute left-1 top-1 w-4 h-4 bg-white rounded-full"></div>
                      </div>
                      <span class="text-sm">beta-analytics</span>
                    </div>
                    <span class="text-xs text-gray-500">0%</span>
                  </div>
                </div>
              </div>
              
              <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <div class="bg-white rounded shadow-sm p-4">
                  <h4 class="text-sm font-semibold text-gray-700 mb-3">Active Flags</h4>
                  <div class="space-y-2">
                    <div class="h-8 bg-primary/10 rounded"></div>
                    <div class="h-8 bg-primary/10 rounded"></div>
                  </div>
                </div>
                <div class="bg-white rounded shadow-sm p-4">
                  <h4 class="text-sm font-semibold text-gray-700 mb-3">Usage Stats</h4>
                  <div class="h-20 bg-gradient-to-r from-primary/20 to-primary/5 rounded flex items-end justify-around px-2 pb-2">
                    <div class="w-8 bg-primary rounded-t" style="height: 60%"></div>
                    <div class="w-8 bg-primary rounded-t" style="height: 80%"></div>
                    <div class="w-8 bg-primary rounded-t" style="height: 45%"></div>
                    <div class="w-8 bg-primary rounded-t" style="height: 90%"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
