<script>
  import { Play, ArrowRight } from 'lucide-svelte';
</script>

<section class="bg-white pt-16 pb-24 px-4 sm:px-6 lg:px-8 flex flex-col items-center text-center font-body overflow-hidden">
  <h1 class="font-display font-bold text-5xl sm:text-7xl md:text-8xl tracking-tight uppercase leading-[0.9] max-w-5xl mx-auto mb-6 text-black">
    The Revenue Operating <br class="hidden sm:block" /> System is Here.
  </h1>
  
  <p class="text-lg sm:text-xl text-gray-600 max-w-2xl mx-auto mb-10 text-balance leading-relaxed">
    One unified platform for your entire GTM team. From first touch to closed won. Finally, everything just works together.
  </p>
  
  <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-16 w-full sm:w-auto">
    <button class="bg-black text-white px-8 py-3 rounded-sm font-medium flex items-center justify-center gap-2 hover:bg-gray-800 transition-colors w-full sm:w-auto group">
      Get started <ArrowRight size={16} class="group-hover:translate-x-1 transition-transform" />
    </button>
    <button class="bg-white text-black border border-gray-200 px-8 py-3 rounded-sm font-medium flex items-center justify-center gap-2 hover:bg-gray-50 transition-colors w-full sm:w-auto">
      See Reevo <Play size={16} fill="currentColor" />
    </button>
  </div>
  
  <!-- Hero Image Container -->
  <div class="relative w-full max-w-6xl mx-auto rounded-xl overflow-hidden shadow-2xl bg-gray-100 aspect-video group cursor-pointer">
    <!-- Placeholder Image Background -->
    <div class="absolute inset-0 bg-gray-200">
        <img src="https://images.unsplash.com/photo-1552664730-d307ca884978?q=80&w=2940&auto=format&fit=crop" alt="Dashboard" class="w-full h-full object-cover opacity-90" />
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
        <div class="w-8 h-8 rounded-full bg-green-100 flex items-center justify-center text-green-600 shrink-0">
          <span class="font-bold text-xs">$</span>
        </div>
        <div>
          <p class="text-sm font-bold text-gray-900">$12k move to late stage pipeline</p>
          <p class="text-xs text-gray-500 mt-0.5">Update sent to #midmarket-sales</p>
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
