<template>
  <section class="bg-white py-20">
    <div class="max-w-6xl mx-auto px-6 text-center">
      <h2 class="text-3xl font-bold text-primary mb-14">
        Why Teams Use IntelliToggle
      </h2>

      <!-- Features -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-10 mb-14">
        <!-- Feature -->
        <div class="flex flex-col items-center text-center">
          <div class="w-14 h-14 mb-6 flex items-center justify-center rounded-lg border border-gray-200 bg-gray-50">
            <img src="/images/rollout.svg" class="w-7 h-7" />
          </div>
          <h3 class="font-semibold text-gray-900 mb-2">Safer, faster rollouts</h3>
          <p class="text-gray-600 text-sm">
            Control feature releases in minutes, not weeks without risking production stability.
          </p>
        </div>

        <div class="flex flex-col items-center text-center">
          <div class="w-14 h-14 mb-6 flex items-center justify-center rounded-lg border border-gray-200 bg-gray-50">
            <img src="/images/ship.svg" class="w-7 h-7" />
          </div>
          <h3 class="font-semibold text-gray-900 mb-2">Confidence to ship</h3>
          <p class="text-gray-600 text-sm">
            “Flip, target, and roll back.” Engineers ship more often knowing they can undo mistakes.
          </p>
        </div>

        <div class="flex flex-col items-center text-center">
          <div class="w-14 h-14 mb-6 flex items-center justify-center rounded-lg border border-gray-200 bg-gray-50">
            <img src="/images/future.svg" class="w-7 h-7" />
          </div>
          <h3 class="font-semibold text-gray-900 mb-2">Future-ready with AI delivery</h3>
          <p class="text-gray-600 text-sm">
            Built for Dart workflows and prepared for AI-powered rollout automation.
          </p>
        </div>
      </div>

      <!-- Case study bar -->
      <div class="flex flex-col md:flex-row items-center justify-between gap-4 bg-gray-100 rounded-lg px-6 py-4">
        <p class="text-sm text-gray-700">
          <span class="font-semibold">Read a 2-min case note:</span>
          How a sample Flutter app shipped faster with IntelliToggle
        </p>
        <button class="bg-orange-500 hover:bg-orange-600 text-white text-sm font-semibold px-5 py-2 rounded-md shadow-sm">
          Read Now
        </button>
      </div>
    </div>
  </section>
</template>
