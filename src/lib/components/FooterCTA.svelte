<script>
  import { ArrowRight, Play } from 'lucide-svelte';
</script>

<section class="bg-white py-24 px-4 sm:px-6 lg:px-8 font-body text-center">
  <div class="max-w-4xl mx-auto">
    <h2 class="font-display font-bold text-5xl sm:text-7xl uppercase leading-[0.9] mb-6 text-black">
      Stop managing software. <br /> Start showing up human.
    </h2>
    
    <p class="text-gray-600 text-lg mb-10">
      Onboarding is easy. Get up and running in minutes.
    </p>
    
    <div class="flex flex-col sm:flex-row items-center justify-center gap-4 w-full sm:w-auto">
      <button class="bg-black text-white px-8 py-3 rounded-sm font-medium flex items-center justify-center gap-2 hover:bg-gray-800 transition-colors w-full sm:w-auto group">
        Get started <ArrowRight size={16} class="group-hover:translate-x-1 transition-transform" />
      </button>
      <button class="bg-white text-black border border-gray-200 px-8 py-3 rounded-sm font-medium flex items-center justify-center gap-2 hover:bg-gray-50 transition-colors w-full sm:w-auto">
        See Reevo <Play size={16} fill="currentColor" />
      </button>
    </div>
  </div>
</section>
