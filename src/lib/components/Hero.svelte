<script>
  import { Play, ArrowRight } from 'lucide-svelte';
</script>

<section class="bg-white pt-16 pb-24 px-4 sm:px-6 lg:px-8 flex flex-col items-center text-center font-body overflow-hidden">
  <h1 class="font-display font-bold text-5xl sm:text-7xl md:text-8xl tracking-tight uppercase leading-[0.9] max-w-5xl mx-auto mb-6 text-black">
    Your Bridge to <br class="hidden sm:block" /> Global Markets.
  </h1>
  
  <p class="text-lg sm:text-xl text-gray-600 max-w-2xl mx-auto mb-10 text-balance leading-relaxed">
    End-to-end global expansion services for Chinese apps, games, and SaaS. From strategy to execution, we handle the complexity so you can focus on growth.
  </p>
  
  <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-16 w-full sm:w-auto">
    <button class="bg-black text-white px-8 py-3 rounded-sm font-medium flex items-center justify-center gap-2 hover:bg-gray-800 transition-colors w-full sm:w-auto group">
      Start expanding <ArrowRight size={16} class="group-hover:translate-x-1 transition-transform" />
    </button>
    <button class="bg-white text-black border border-gray-200 px-8 py-3 rounded-sm font-medium flex items-center justify-center gap-2 hover:bg-gray-50 transition-colors w-full sm:w-auto">
      See our work <Play size={16} fill="currentColor" />
    </button>
  </div>
  
  <!-- Hero Image Container -->
  <div class="relative w-full max-w-6xl mx-auto rounded-xl overflow-hidden shadow-2xl bg-gray-100 aspect-video group cursor-pointer">
    <!-- Placeholder Image Background -->
    <div class="absolute inset-0 bg-gray-200">
        <img src="/generated/image-diverse-international-business-team-coll-1767923524863-0.webp" alt="International business collaboration" class="w-full h-full object-cover opacity-90" />
    </div>
    
    <!-- Play Button Overlay -->
    <div class="absolute inset-0 flex items-center justify-center">
      <div class="w-20 h-20 bg-black/80 backdrop-blur-sm rounded-sm flex items-center justify-center text-white hover:scale-105 transition-transform duration-300">
        <Play size={32} fill="white" />
      </div>
    </div>
    
    <!-- Notification Toast -->
    <div class="absolute bottom-8 right-8 bg-white/90 backdrop-blur-md p-4 rounded-lg shadow-lg border border-white/20 max-w-xs text-left animate-bounce-slow hidden md:block">
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 rounded-full bg-primary-100 flex items-center justify-center text-primary-600 shrink-0">
          <span class="font-bold text-xs">🌍</span>
        </div>
        <div>
          <p class="text-sm font-bold text-gray-900">New market launch: 50K users in 30 days</p>
          <p class="text-xs text-gray-500 mt-0.5">North America expansion complete</p>
        </div>
      </div>
    </div>
  </div>
</section>

<style>
  @keyframes bounce-slow {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-5px); }
  }
  .animate-bounce-slow {
    animation: bounce-slow 3s infinite ease-in-out;
  }
</style>
