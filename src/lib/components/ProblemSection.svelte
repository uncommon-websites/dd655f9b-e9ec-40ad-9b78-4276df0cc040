<script>
  import { ArrowRight } from 'lucide-svelte';
</script>

<section class="bg-gray-950 text-white py-24 px-4 sm:px-6 lg:px-8 font-body relative overflow-hidden">
  <!-- Top Pattern -->
  <div class="absolute top-0 left-0 w-full h-24 opacity-20 pointer-events-none bg-[url('https://grainy-gradients.vercel.app/noise.svg')]"></div>
  <div class="absolute top-0 left-0 w-full h-12 opacity-20" 
       style="background-image: linear-gradient(90deg, rgba(255,255,255,0.5) 1px, transparent 1px), linear-gradient(rgba(255,255,255,0.5) 1px, transparent 1px); background-size: 4px 4px;">
  </div>
  <div class="absolute top-0 left-0 w-full h-12 bg-gradient-to-b from-gray-950/0 to-gray-950"></div>

  <!-- Bottom Pattern -->
   <div class="absolute bottom-0 left-0 w-full h-12 opacity-20" 
       style="background-image: linear-gradient(90deg, rgba(255,255,255,0.5) 1px, transparent 1px), linear-gradient(rgba(255,255,255,0.5) 1px, transparent 1px); background-size: 4px 4px;">
  </div>
  <div class="absolute bottom-0 left-0 w-full h-12 bg-gradient-to-t from-gray-950/0 to-gray-950"></div>

  <div class="max-w-7xl mx-auto relative z-10">
    <!-- Header -->
    <div class="mb-20">
      <div class="flex items-center gap-2 mb-6">
        <div class="w-5 h-5 bg-white text-black flex items-center justify-center text-xs font-bold rounded-sm">O</div>
        <span class="text-xs font-bold tracking-widest uppercase text-gray-400">The Problem</span>
      </div>
      
      <h2 class="font-display font-medium text-4xl sm:text-5xl max-w-4xl leading-tight">
        Your sales stack is a dinosaur, <span class="text-gray-500">your reps live in a dozen different tabs, and your "AI" is just a fancy autocomplete.</span>
      </h2>
      
      <p class="mt-8 text-sm font-bold text-gray-400 uppercase tracking-wider">It creates 3 things we call:</p>
    </div>

    <!-- Cards Grid -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <!-- Card 1 -->
      <div class="group">
        <div class="aspect-square bg-gray-900 rounded-sm overflow-hidden mb-6 relative">
          <img src="https://images.unsplash.com/photo-1531403009284-440f080d1e12?q=80&w=2940&auto=format&fit=crop" alt="Integration tax" class="w-full h-full object-cover grayscale opacity-80 group-hover:opacity-100 group-hover:scale-105 transition-all duration-500" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>
        </div>
        <h3 class="font-bold text-xl mb-3">The integration tax</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Paying engineers and RevOps to constantly fix the brittle APIs connecting your maze of point solutions. Stop subsidizing bad architecture.
        </p>
      </div>

      <!-- Card 2 -->
      <div class="group">
        <div class="aspect-square bg-gray-900 rounded-sm overflow-hidden mb-6 relative">
          <img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?q=80&w=2940&auto=format&fit=crop" alt="Swivel chair workflow" class="w-full h-full object-cover grayscale opacity-80 group-hover:opacity-100 group-hover:scale-105 transition-all duration-500" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>
        </div>
        <h3 class="font-bold text-xl mb-3">The swivel chair workflow</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Your reps are juggling 8+ tabs just to book a meeting and log a call. That's not selling; that's high-cost data entry.
        </p>
      </div>

      <!-- Card 3 -->
      <div class="group">
        <div class="aspect-square bg-gray-900 rounded-sm overflow-hidden mb-6 relative">
          <img src="https://images.unsplash.com/photo-1551836022-d5d88e9218df?q=80&w=2940&auto=format&fit=crop" alt="Fake AI problem" class="w-full h-full object-cover grayscale opacity-80 group-hover:opacity-100 group-hover:scale-105 transition-all duration-500" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>
        </div>
        <h3 class="font-bold text-xl mb-3">The "Fake AI" problem</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          You can't build real intelligence on fragmented data. If your tools don't talk to each other, your "AI" is just guessing.
        </p>
      </div>
    </div>
  </div>
</section>
