<template>
  <section class="bg-white py-16 md:py-24">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8">
      <div class="max-w-6xl mx-auto">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
          <!-- Left Side - Logo and Visual -->
          <div class="flex items-center justify-center">
            <div class="bg-gradient-to-br from-gray-50 to-gray-100 rounded-2xl p-12 lg:p-16 shadow-lg">
              <div class="text-center">
                <div class="inline-flex items-center justify-center w-16 h-16 bg-white rounded-full shadow-md mb-6">
                  <span class="text-3xl">🚀</span>
                </div>
                <h3 class="text-4xl md:text-5xl font-bold text-gray-900 mb-2">
                  Open<br />Feature
                </h3>
                <div class="w-16 h-1 bg-accent-orange mx-auto mt-4"></div>
              </div>
            </div>
          </div>

          <!-- Right Side - Content -->
          <div>
            <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6">
              Seamless Feature Management with OpenFeature
            </h2>
            
            <p class="text-gray-600 leading-relaxed mb-6">
              IntelliToggle is built on OpenFeature, the open standard for feature flagging. This means you get vendor-neutral feature management with the flexibility to switch providers or use multiple providers simultaneously.
            </p>

            <div class="space-y-4 mb-8">
              <div class="flex items-start">
                <div class="w-6 h-6 bg-green-100 rounded-full flex items-center justify-center mr-3 mt-0.5 flex-shrink-0">
                  <svg class="w-4 h-4 text-green-600" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                  </svg>
                </div>
                <div>
                  <h4 class="font-semibold text-gray-900">Vendor-Neutral Standard</h4>
                  <p class="text-gray-600 text-sm">No lock-in, freedom to choose</p>
                </div>
              </div>

              <div class="flex items-start">
                <div class="w-6 h-6 bg-green-100 rounded-full flex items-center justify-center mr-3 mt-0.5 flex-shrink-0">
                  <svg class="w-4 h-4 text-green-600" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                  </svg>
                </div>
                <div>
                  <h4 class="font-semibold text-gray-900">Community-Driven</h4>
                  <p class="text-gray-600 text-sm">Open source with active community support</p>
                </div>
              </div>

              <div class="flex items-start">
                <div class="w-6 h-6 bg-green-100 rounded-full flex items-center justify-center mr-3 mt-0.5 flex-shrink-0">
                  <svg class="w-4 h-4 text-green-600" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                  </svg>
                </div>
                <div>
                  <h4 class="font-semibold text-gray-900">Multi-Provider Support</h4>
                  <p class="text-gray-600 text-sm">Use multiple feature flag providers together</p>
                </div>
              </div>
            </div>

            <button class="bg-accent-orange hover:bg-orange-500 text-white px-6 py-3 rounded-md font-semibold transition-colors">
              Explore OpenFeature
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
