<template>
  <section class="bg-gray-50 py-16 md:py-24">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center mb-12">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
          Control & Power-focused
        </h2>
      </div>

      <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-6 lg:gap-8">
        <!-- Card 1: Dark Mode -->
        <div class="group bg-white rounded-xl overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-2">
          <div class="bg-gray-900 h-48 relative overflow-hidden">
            <!-- Mock Terminal/Dark Interface -->
            <div class="absolute inset-0 p-4 font-mono text-xs">
              <div class="text-green-400 mb-2">$ intellitoggle init</div>
              <div class="text-gray-400 mb-1">Initializing feature flags...</div>
              <div class="text-green-400 mb-1">✓ Connected to dashboard</div>
              <div class="text-green-400 mb-1">✓ 5 flags loaded</div>
              <div class="text-gray-400 mb-1">Ready to toggle!</div>
              <div class="text-green-400 animate-pulse">▊</div>
            </div>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-bold text-gray-900 mb-3">Dark Mode</h3>
            <p class="text-gray-600 text-sm leading-relaxed">
              Built for developers who love working in dark mode. Our interface adapts to your preferences seamlessly.
            </p>
            <button class="mt-4 text-accent-orange hover:text-orange-600 font-semibold text-sm flex items-center group-hover:gap-2 transition-all">
              Learn more 
              <svg class="w-4 h-4 ml-1 group-hover:ml-2 transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
              </svg>
            </button>
          </div>
        </div>

        <!-- Card 2: Real-time -->
        <div class="group bg-white rounded-xl overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-2">
          <div class="bg-gradient-to-br from-primary to-primary-dark h-48 relative overflow-hidden flex items-center justify-center">
            <!-- Mock Real-time Dashboard -->
            <div class="text-center text-white">
              <div class="text-5xl font-bold mb-2">247</div>
              <div class="text-sm opacity-80 mb-4">Active Users</div>
              <div class="flex items-center justify-center gap-2">
                <div class="w-2 h-2 bg-green-400 rounded-full animate-pulse"></div>
                <span class="text-xs">Live Updates</span>
              </div>
            </div>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-bold text-gray-900 mb-3">Real-time</h3>
            <p class="text-gray-600 text-sm leading-relaxed">
              See changes instantly. Monitor feature flag usage and user engagement in real-time with live dashboards.
            </p>
            <button class="mt-4 text-accent-orange hover:text-orange-600 font-semibold text-sm flex items-center group-hover:gap-2 transition-all">
              Learn more 
              <svg class="w-4 h-4 ml-1 group-hover:ml-2 transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
              </svg>
            </button>
          </div>
        </div>

        <!-- Card 3: Kill Switches -->
        <div class="group bg-white rounded-xl overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-2">
          <div class="bg-red-50 h-48 relative overflow-hidden flex items-center justify-center">
            <!-- Mock Kill Switch Interface -->
            <div class="text-center">
              <div class="inline-flex items-center justify-center w-20 h-20 bg-red-500 rounded-full mb-4 shadow-lg">
                <svg class="w-10 h-10 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                </svg>
              </div>
              <div class="text-sm font-semibold text-gray-700">Emergency Override</div>
            </div>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-bold text-gray-900 mb-3">Kill Switches</h3>
            <p class="text-gray-600 text-sm leading-relaxed">
              Instantly disable problematic features with one click. No deployment needed. Perfect for emergency situations.
            </p>
            <button class="mt-4 text-accent-orange hover:text-orange-600 font-semibold text-sm flex items-center group-hover:gap-2 transition-all">
              Learn more 
              <svg class="w-4 h-4 ml-1 group-hover:ml-2 transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
              </svg>
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
