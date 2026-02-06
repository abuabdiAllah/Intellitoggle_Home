<template>
  <section class="bg-primary-dark text-white py-16 md:py-24 relative overflow-hidden">
    <!-- Background Pattern -->
    <div class="absolute inset-0 opacity-10">
      <div class="absolute inset-0" style="background-image: repeating-linear-gradient(45deg, transparent, transparent 35px, rgba(255,255,255,.1) 35px, rgba(255,255,255,.1) 70px);"></div>
    </div>

    <div class="container mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
      <div class="text-center mb-12">
        <span class="inline-block bg-accent-yellow text-primary px-4 py-1 rounded-full text-sm font-semibold mb-4">
          Enterprise Only
        </span>
        <h2 class="text-3xl md:text-4xl font-bold mb-4">
          DartCodeAI That Actually Changes Flagging
        </h2>
      </div>

      <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
        <!-- Feature 1 -->
        <div class="text-center">
          <div class="w-16 h-16 bg-white/10 rounded-lg flex items-center justify-center mx-auto mb-4 backdrop-blur-sm">
            <svg class="w-8 h-8 text-accent-orange" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" />
            </svg>
          </div>
          <h3 class="font-semibold text-lg mb-2">Smart Rollouts</h3>
          <p class="text-white/70 text-sm">
            AI-powered gradual rollouts that adapt to user behavior and system metrics
          </p>
        </div>

        <!-- Feature 2 -->
        <div class="text-center">
          <div class="w-16 h-16 bg-white/10 rounded-lg flex items-center justify-center mx-auto mb-4 backdrop-blur-sm">
            <svg class="w-8 h-8 text-accent-orange" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
            </svg>
          </div>
          <h3 class="font-semibold text-lg mb-2">Lightning Fast Edge</h3>
          <p class="text-white/70 text-sm">
            Evaluate flags at the edge with <1ms latency globally
          </p>
        </div>

        <!-- Feature 3 -->
        <div class="text-center">
          <div class="w-16 h-16 bg-white/10 rounded-lg flex items-center justify-center mx-auto mb-4 backdrop-blur-sm">
            <svg class="w-8 h-8 text-accent-orange" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" />
            </svg>
          </div>
          <h3 class="font-semibold text-lg mb-2">Advanced Targeting</h3>
          <p class="text-white/70 text-sm">
            Target users by attributes, segments, or custom rules with precision
          </p>
        </div>

        <!-- Feature 4 -->
        <div class="text-center">
          <div class="w-16 h-16 bg-white/10 rounded-lg flex items-center justify-center mx-auto mb-4 backdrop-blur-sm">
            <svg class="w-8 h-8 text-accent-orange" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4" />
            </svg>
          </div>
          <h3 class="font-semibold text-lg mb-2">Multi-Environment</h3>
          <p class="text-white/70 text-sm">
            Seamlessly manage flags across dev, staging, and production
          </p>
        </div>

        <!-- Feature 5 -->
        <div class="text-center">
          <div class="w-16 h-16 bg-white/10 rounded-lg flex items-center justify-center mx-auto mb-4 backdrop-blur-sm">
            <svg class="w-8 h-8 text-accent-orange" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 12l3-3 3 3 4-4M8 21l4-4 4 4M3 4h18M4 4h16v12a1 1 0 01-1 1H5a1 1 0 01-1-1V4z" />
            </svg>
          </div>
          <h3 class="font-semibold text-lg mb-2">Detailed Analytics</h3>
          <p class="text-white/70 text-sm">
            Track flag usage, performance impact, and user engagement metrics
          </p>
        </div>

        <!-- Feature 6 -->
        <div class="text-center">
          <div class="w-16 h-16 bg-white/10 rounded-lg flex items-center justify-center mx-auto mb-4 backdrop-blur-sm">
            <svg class="w-8 h-8 text-accent-orange" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z" />
            </svg>
          </div>
          <h3 class="font-semibold text-lg mb-2">Team Collaboration</h3>
          <p class="text-white/70 text-sm">
            Role-based access control and approval workflows for safe releases
          </p>
        </div>

        <!-- Feature 7 -->
        <div class="text-center">
          <div class="w-16 h-16 bg-white/10 rounded-lg flex items-center justify-center mx-auto mb-4 backdrop-blur-sm">
            <svg class="w-8 h-8 text-accent-orange" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z" />
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
            </svg>
          </div>
          <h3 class="font-semibold text-lg mb-2">API & Webhooks</h3>
          <p class="text-white/70 text-sm">
            Comprehensive API and webhook system for custom integrations
          </p>
        </div>

        <!-- Feature 8 -->
        <div class="text-center">
          <div class="w-16 h-16 bg-white/10 rounded-lg flex items-center justify-center mx-auto mb-4 backdrop-blur-sm">
            <svg class="w-8 h-8 text-accent-orange" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z" />
            </svg>
          </div>
          <h3 class="font-semibold text-lg mb-2">Enterprise Security</h3>
          <p class="text-white/70 text-sm">
            SOC 2 compliant with SSO, audit logs, and data encryption
          </p>
        </div>
      </div>

      <div class="text-center mt-12">
        <button class="bg-accent-orange hover:bg-orange-500 text-white px-8 py-3 rounded-md font-semibold transition-colors">
          Enterprise Only
        </button>
      </div>
    </div>
  </section>
</template>
