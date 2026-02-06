<template>
  <footer class="bg-[#ECEBF5] py-16">
    <div class="max-w-7xl mx-auto px-6">
      <div class="grid grid-cols-1 md:grid-cols-4 gap-12">

        <!-- Logo & description -->
        <div>
          <div class="flex items-center gap-3 mb-4">
            <img src="/images/logoPurple.svg" class="h-8 w-auto" />
            <span class="font-semibold text-lg text-gray-900">IntelliToggle</span>
          </div>

          <p class="text-gray-600 text-sm max-w-xs leading-relaxed">
            IntelliToggle is built by AORTEM, a company focused on powering scalable, multi-platform developer tools.
          </p>

          <div class="mt-6">
            <div class="w-9 h-9 rounded-full bg-gray-300 flex items-center justify-center">
              <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"> <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd" /> </svg>
            </div>
          </div>
        </div>

        <!-- Resources -->
        <div>
          <h4 class="font-semibold text-gray-900 mb-4">Resources</h4>
          <ul class="space-y-3 text-sm text-gray-600">
            <li class="hover:text-gray-900 cursor-pointer">Why IntelliToggle Is Different</li>
            <li class="hover:text-gray-900 cursor-pointer">Customer Support</li>
            <li class="hover:text-gray-900 cursor-pointer">Terms & Conditions</li>
            <li class="hover:text-gray-900 cursor-pointer">Privacy Policy</li>
          </ul>
        </div>

        <!-- Company -->
        <div>
          <h4 class="font-semibold text-gray-900 mb-4">Company</h4>
          <ul class="space-y-3 text-sm text-gray-600">
            <li class="hover:text-gray-900 cursor-pointer">Pricing</li>
            <li class="hover:text-gray-900 cursor-pointer">Documentation</li>
            <li class="hover:text-gray-900 cursor-pointer">About Us</li>
          </ul>
        </div>

        <!-- Newsletter -->
        <div>
          <h4 class="font-semibold text-gray-900 mb-4">
            Subscribe to Newsletter
          </h4>

         <div class="flex w-full bg-white rounded-md shadow-sm overflow-hidden h-11">
            <input
              type="email"
              placeholder="Enter email address"
              class="flex-1 min-w-0 px-3 text-sm outline-none placeholder-gray-400"
            />

            <button
              class="flex-shrink-0 bg-orange-500 hover:bg-orange-600 text-white px-5 text-sm font-semibold flex items-center justify-center"
            >
              Subscribe
            </button>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

