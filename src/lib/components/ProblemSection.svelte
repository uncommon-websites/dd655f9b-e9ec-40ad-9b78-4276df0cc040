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
        <div class="w-5 h-5 bg-white text-black flex items-center justify-center text-xs font-bold rounded-sm">!</div>
        <span class="text-xs font-bold tracking-widest uppercase text-gray-400">The Challenge</span>
      </div>
      
      <h2 class="font-display font-medium text-4xl sm:text-5xl max-w-4xl leading-tight">
        Global expansion is complex, <span class="text-gray-500">and going it alone means navigating regulatory mazes, cultural barriers, and fragmented vendor relationships.</span>
      </h2>
      
      <p class="mt-8 text-sm font-bold text-gray-400 uppercase tracking-wider">Chinese companies face 3 critical barriers:</p>
    </div>

    <!-- Cards Grid -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <!-- Card 1 -->
      <div class="group">
        <div class="aspect-square bg-gray-900 rounded-sm overflow-hidden mb-6 relative">
          <img src="https://images.unsplash.com/photo-1589829545856-d10d557cf95f?q=80&w=2940&auto=format&fit=crop" alt="Regulatory complexity" class="w-full h-full object-cover grayscale opacity-80 group-hover:opacity-100 group-hover:scale-105 transition-all duration-500" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>
        </div>
        <h3 class="font-bold text-xl mb-3">The regulatory maze</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Every market has unique compliance requirements, data privacy laws, and business registration processes. One misstep can derail your entire launch.
        </p>
      </div>

      <!-- Card 2 -->
      <div class="group">
        <div class="aspect-square bg-gray-900 rounded-sm overflow-hidden mb-6 relative">
          <img src="https://images.unsplash.com/photo-1523240795612-9a054b0db644?q=80&w=2940&auto=format&fit=crop" alt="Cultural barriers" class="w-full h-full object-cover grayscale opacity-80 group-hover:opacity-100 group-hover:scale-105 transition-all duration-500" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>
        </div>
        <h3 class="font-bold text-xl mb-3">The localization gap</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Direct translation isn't localization. Without deep cultural understanding and local market expertise, your message gets lost in translation.
        </p>
      </div>

      <!-- Card 3 -->
      <div class="group">
        <div class="aspect-square bg-gray-900 rounded-sm overflow-hidden mb-6 relative">
          <img src="https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?q=80&w=2940&auto=format&fit=crop" alt="Vendor fragmentation" class="w-full h-full object-cover grayscale opacity-80 group-hover:opacity-100 group-hover:scale-105 transition-all duration-500" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>
        </div>
        <h3 class="font-bold text-xl mb-3">The vendor juggling act</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Managing separate agencies for legal, marketing, localization, and tech infrastructure creates coordination nightmares and accountability gaps.
        </p>
      </div>
    </div>
  </div>
</section>
