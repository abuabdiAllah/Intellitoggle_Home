<template>
  <section class="bg-gray-50 py-16 md:py-24">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8">
      <!-- Centered Title -->
      <div class="text-center mb-12">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-900">
          What is IntelliToggle
        </h2>
      </div>

      <div class="max-w-6xl mx-auto">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
          <!-- Left Content - Center Aligned -->
          <div class="text-center lg:text-left">
            <h3 class="text-xl font-semibold text-gray-900 mb-3">
              Your AI Dart App's Control Panel For Feature Releases
            </h3>
            <p class="text-gray-600 leading-relaxed mb-6">
              IntelliToggle is a “Dart-Powered” feature flag that lets you turn features on/off instantly in your application without redeploying code. It allows you control roll-outs, run experiments, and fix bugs faster.
            </p>

            <div class="mb-6">
              <h4 class="font-semibold text-gray-900 mb-2">Benefits:</h4>
              <ul class="space-y-2 text-gray-600 text-left inline-block list-disc list-inside">
                <li>Toggle new features without app updates</li>
                <li>Roll out to specific users or regions</li>
                <li>Instantly rollback when needed</li>
              </ul>
            </div>
          </div>

          <!-- Right Image/Dashboard -->
          <div class="relative">
            <img 
              src="/public/images/whatIs.png" 
              alt="IntelliToggle Dashboard" 
              class="w-full rounded-lg shadow-2xl"
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>