<template>
  <section class="bg-gray-50 py-16 md:py-24">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8">
      <div class="max-w-6xl mx-auto">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
          <!-- Left Content -->
          <div>
            <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6">
              What is IntelliToggle
            </h2>
            
            <div class="space-y-6">
              <div>
                <h3 class="text-xl font-semibold text-gray-900 mb-3">
                  Feature Flag Control Panel For Feature Releases
                </h3>
                <p class="text-gray-600 leading-relaxed">
                  IntelliToggle is a powerful feature flag management platform that gives you complete control over your feature releases. Deploy features safely, test in production, and roll back instantly without code changes.
                </p>
              </div>

              <div>
                <h4 class="font-semibold text-gray-900 mb-2">Benefits:</h4>
                <ul class="space-y-2 text-gray-600">
                  <li class="flex items-start">
                    <svg class="w-5 h-5 text-green-500 mr-2 mt-0.5 flex-shrink-0" fill="currentColor" viewBox="0 0 20 20">
                      <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                    </svg>
                    <span>Deploy features independently from code releases</span>
                  </li>
                  <li class="flex items-start">
                    <svg class="w-5 h-5 text-green-500 mr-2 mt-0.5 flex-shrink-0" fill="currentColor" viewBox="0 0 20 20">
                      <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                    </svg>
                    <span>Test in production with specific user segments</span>
                  </li>
                  <li class="flex items-start">
                    <svg class="w-5 h-5 text-green-500 mr-2 mt-0.5 flex-shrink-0" fill="currentColor" viewBox="0 0 20 20">
                      <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                    </svg>
                    <span>Instant rollback without redeploying</span>
                  </li>
                  <li class="flex items-start">
                    <svg class="w-5 h-5 text-green-500 mr-2 mt-0.5 flex-shrink-0" fill="currentColor" viewBox="0 0 20 20">
                      <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                    </svg>
                    <span>Percentage-based gradual rollouts</span>
                  </li>
                </ul>
              </div>

              <button class="bg-accent-orange hover:bg-orange-500 text-white px-6 py-3 rounded-md font-semibold transition-colors">
                Learn More
              </button>
            </div>
          </div>

          <!-- Right Image/Dashboard -->
          <div class="relative">
            <div class="bg-primary rounded-lg shadow-2xl overflow-hidden p-4 transform rotate-2 hover:rotate-0 transition-transform duration-300">
              <div class="bg-white rounded p-4">
                <div class="flex items-center justify-between mb-4">
                  <h4 class="font-semibold text-gray-800 text-sm">Analytics Dashboard</h4>
                  <div class="flex gap-2">
                    <div class="w-2 h-2 rounded-full bg-gray-300"></div>
                    <div class="w-2 h-2 rounded-full bg-gray-300"></div>
                    <div class="w-2 h-2 rounded-full bg-gray-300"></div>
                  </div>
                </div>
                
                <!-- Chart Area -->
                <div class="bg-gray-50 rounded p-4 h-48 flex items-end justify-around gap-2">
                  <div class="flex-1 bg-primary rounded-t" style="height: 40%"></div>
                  <div class="flex-1 bg-primary rounded-t" style="height: 70%"></div>
                  <div class="flex-1 bg-primary rounded-t" style="height: 45%"></div>
                  <div class="flex-1 bg-primary rounded-t" style="height: 85%"></div>
                  <div class="flex-1 bg-primary rounded-t" style="height: 60%"></div>
                  <div class="flex-1 bg-primary rounded-t" style="height: 90%"></div>
                  <div class="flex-1 bg-primary rounded-t" style="height: 75%"></div>
                </div>

                <!-- Stats -->
                <div class="grid grid-cols-3 gap-4 mt-4">
                  <div class="bg-gray-50 rounded p-2 text-center">
                    <div class="text-xs text-gray-500">Active</div>
                    <div class="text-lg font-bold text-primary">24</div>
                  </div>
                  <div class="bg-gray-50 rounded p-2 text-center">
                    <div class="text-xs text-gray-500">Users</div>
                    <div class="text-lg font-bold text-primary">1.2K</div>
                  </div>
                  <div class="bg-gray-50 rounded p-2 text-center">
                    <div class="text-xs text-gray-500">Rollout</div>
                    <div class="text-lg font-bold text-primary">85%</div>
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
