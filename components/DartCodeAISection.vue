<template>
  <section class="relative py-24 overflow-hidden">
    <!-- Background -->
    <div
      class="absolute inset-0 bg-cover bg-center"
      style="background-image: url('/images/backgroundAI.png')"
    />
    <div class="absolute inset-0 bg-gradient-to-b from-[#0b0f2a]/60 via-[#0b0f2a]/40 to-[#0b0f2a]/70" />

    <!-- Content -->
    <div class="relative max-w-7xl mx-auto px-6 text-white">
      <!-- Badge -->
      <div class="flex justify-center mb-6">
        <span class="bg-accent-orange text-black text-sm font-semibold px-4 py-1 rounded-full">
          Coming Soon
        </span>
      </div>

      <!-- Title -->
      <h2 class="text-center text-4xl font-bold mb-16">
        DartCodeAI That Actually Changes Flagging
      </h2>

      <!-- Cards -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div
          v-for="(feature, i) in features"
          :key="i"
          class="relative bg-white/10 backdrop-blur border border-white/20 rounded-xl p-6"
        >
          <!-- Icon -->
          <div
            class="w-10 h-10 mx-auto flex items-center justify-center
         bg-white/90 rounded-md mb-4""
          >
            <img
              :src="feature.icon"
              alt=""
              class="w-5 h-5"
            />
          </div>

          <!-- Text -->
          <h3 class="text-xl font-bold mb-2 text-center">
            {{ feature.title }}
            <span class="font-normal opacity-80">{{ feature.subtitle }}</span>
          </h3>

          <p class="text-sm text-white/80 leading-relaxed text-center">
            {{ feature.description }}
          </p>
        </div>
      </div>

      <!-- Enterprise -->
      <p class="text-center text-accent-orange font-semibold mt-16">
        Enterprise Only
      </p>

      <!-- CTA -->
      <div
        class="mt-8 bg-white/10 border border-white/20 rounded-xl p-6
               flex flex-col md:flex-row items-center justify-between gap-4"
      >
        <p class="text-lg font-semibold">
          Be The First To Try Out Our New AI Features.
        </p>

        <div class="flex gap-3 w-full md:w-auto">
          <input
            type="email"
            placeholder="Enter email address"
            class="w-full md:w-64 px-4 py-2 rounded bg-white/90 text-black focus:outline-none"
          />
          <button class="bg-accent-orange text-black px-6 py-2 rounded font-semibold">
            Join AI Early Access
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const features = [
  {
    title: 'AutoFlag AI',
    subtitle: '(LLM-Assisted Flag Creation)',
    description:
      'Create new flags just by typing what you need. The AI names it, sets rules, and configures targeting for you.',
      icon: '/images/flag.svg',
  },
  {
    title: 'SmartRamp AI',
    subtitle: '(AI-Driven Rollout Optimization)',
    description:
      'Rollouts that adjust themselves. AI expands, pauses, or rolls back based on real-time metrics.',
      icon: '/images/robot.svg',
  },
  {
    title: 'ExplainFlags AI',
    subtitle: '(LLM Root-Cause + Insights)',
    description:
      'Understand issues instantly with AI-generated, plain-language insights tied to your flags.',
      icon: '/images/mag.svg',
  },
  {
    title: 'AutoSegment AI',
    subtitle: '(Behavioral Segmentation)',
    description:
      'Target the right users automatically. AI builds segments from live behavior—no manual rules.',
      icon: '/images/stats.svg',
  },
]
</script>
