<section class="bg-gray-100 py-24 px-4 sm:px-6 lg:px-8 font-body">
  <div class="max-w-7xl mx-auto">
    <div class="relative bg-black rounded-sm overflow-hidden h-[500px] flex items-end">
        <!-- Background Image -->
        <img src="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?q=80&w=2787&auto=format&fit=crop" alt="Nate" class="absolute inset-0 w-full h-full object-cover grayscale opacity-60" />
        
        <!-- Content Overlay -->
        <div class="relative z-10 p-8 sm:p-12 md:p-16 max-w-4xl ml-auto">
            <blockquote class="text-2xl sm:text-3xl font-bold text-white leading-tight mb-8">
                "Coming from HubSpot, Reevo was truly a breath of fresh air. Their vertically integrated platform for outbound sales and AI-first workflow has made spinning up campaigns a breeze for us, and we're booking meetings at a steady clip with their outbound tools. The Reevo team has been the best vendor we've ever worked with, and they continue to ship huge updates at breakneck pace. The future is bright for these guys."
            </blockquote>
            
            <div class="bg-white/10 backdrop-blur-sm inline-block px-4 py-3 rounded-sm border border-white/20">
                <p class="text-white font-bold text-xs uppercase tracking-wider">Nate</p>
                <p class="text-gray-300 text-[10px] font-bold uppercase tracking-wider mt-1">Digital Marketing Manager, Solarfit</p>
            </div>
        </div>
        
        <!-- Decorative pattern -->
        <div class="absolute top-10 left-10 w-24 h-24 opacity-50 hidden md:block">
             <div class="grid grid-cols-4 gap-1">
                {#each Array(16) as _}
                    <div class="w-1 h-1 bg-green-400 rounded-full"></div>
                {/each}
             </div>
        </div>
    </div>
  </div>
</section>
