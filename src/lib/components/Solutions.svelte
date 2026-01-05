<script>
  import { ArrowRight } from 'lucide-svelte';

  const solutions = [
    {
      tag: "FIND",
      title: "ZERO IN ON THE BUYERS WHO MATTER",
      description: "Build, refine, and activate your ideal lead list directly within Reevo. We automatically dedupe and map new contacts to accounts so your data is always clean and actionable.",
      color: "bg-orange-50",
      accent: "bg-orange-500",
      textAccent: "text-orange-600",
      image: "https://images.unsplash.com/photo-1551288049-bebda4e38f71?q=80&w=2940&auto=format&fit=crop" // Dashboard/List view
    },
    {
      tag: "CONNECT",
      title: "BUILD PIPELINE WITHOUT THE PATCHWORK",
      description: "Dialer, multi-channel sequences, and email deliverability tools built directly into your CRM. Manage your entire outreach without ever switching tabs.",
      color: "bg-pink-50",
      accent: "bg-pink-500",
      textAccent: "text-pink-600",
      image: "https://images.unsplash.com/photo-1460925895917-afdab827c52f?q=80&w=2426&auto=format&fit=crop" // Analytics/Sequence view
    },
    {
      tag: "SELL",
      title: "TURN CONVERSATIONS INTO CONVERSIONS",
      description: "Use natively built AI tools to distill call insights, generate tasks, and draft follow-up emails with relevant context, so you keep momentum strong.",
      color: "bg-green-50",
      accent: "bg-green-500",
      textAccent: "text-green-600",
      image: "https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?q=80&w=2788&auto=format&fit=crop" // Video call/Person
    },
    {
      tag: "MANAGE",
      title: "OPERATE FROM A SINGLE SOURCE OF TRUTH",
      description: "Your pipeline manages itself with automated activity logging and stage gating. You can trust your forecast because it's based on real activity, not manual updates.",
      color: "bg-yellow-50",
      accent: "bg-yellow-500",
      textAccent: "text-yellow-600",
      image: "https://images.unsplash.com/photo-1551288049-bebda4e38f71?q=80&w=2940&auto=format&fit=crop" // Chart view
    }
  ];
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 font-body">
  <div class="max-w-7xl mx-auto">
    <!-- Header -->
    <div class="mb-24">
      <div class="flex items-center gap-2 mb-6">
        <div class="w-5 h-5 bg-black text-white flex items-center justify-center text-xs font-bold rounded-sm">R</div>
        <span class="text-xs font-bold tracking-widest uppercase text-gray-500">The Solution: Reevo</span>
      </div>
      
      <h2 class="font-display font-medium text-4xl sm:text-5xl max-w-4xl leading-tight text-gray-900">
        Prospect-to-close in a single tab. <br />
        <span class="text-gray-500">More functionality. Less complexity. No "stack" required.</span>
      </h2>
    </div>

    <!-- Solutions List -->
    <div class="space-y-32">
      {#each solutions as solution, i}
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 lg:gap-24 items-center">
          <!-- Text Content -->
          <div class="order-1">
            <span class={`text-[10px] font-bold px-2 py-1 rounded uppercase tracking-wider mb-6 inline-block ${solution.color} ${solution.textAccent}`}>
              {solution.tag}
            </span>
            
            <h3 class="font-display font-bold text-4xl sm:text-5xl uppercase leading-[0.9] mb-6 text-gray-900">
              {solution.title}
            </h3>
            
            <p class="text-gray-600 text-lg leading-relaxed mb-8 max-w-md">
              {solution.description}
            </p>
            
            <button class="flex items-center gap-2 border border-gray-300 rounded-sm px-6 py-3 text-sm font-medium hover:bg-gray-50 transition-colors group">
              Learn more <ArrowRight size={16} class="group-hover:translate-x-1 transition-transform" />
            </button>
          </div>
          
          <!-- Image Content -->
          <div class={`order-2 relative rounded-xl overflow-hidden shadow-xl aspect-[4/3] group ${solution.color} p-8 flex items-center justify-center`}>
             <!-- Abstract UI representation -->
             <div class="bg-white rounded-lg shadow-2xl w-full h-full overflow-hidden relative transform group-hover:scale-[1.02] transition-transform duration-500">
                <!-- Fake UI Header -->
                <div class="h-8 border-b border-gray-100 flex items-center px-4 gap-2">
                    <div class="w-2 h-2 rounded-full bg-red-400"></div>
                    <div class="w-2 h-2 rounded-full bg-yellow-400"></div>
                    <div class="w-2 h-2 rounded-full bg-green-400"></div>
                </div>
                <!-- Fake UI Body -->
                <div class="p-4">
                    <div class="w-1/3 h-4 bg-gray-100 rounded mb-4"></div>
                    <div class="space-y-2">
                        <div class="w-full h-2 bg-gray-50 rounded"></div>
                        <div class="w-5/6 h-2 bg-gray-50 rounded"></div>
                        <div class="w-4/6 h-2 bg-gray-50 rounded"></div>
                    </div>
                     <div class="mt-8 grid grid-cols-3 gap-4">
                        <div class="h-20 bg-gray-50 rounded"></div>
                        <div class="h-20 bg-gray-50 rounded"></div>
                        <div class="h-20 bg-gray-50 rounded"></div>
                    </div>
                </div>
                <!-- Overlay Image (actual visual) -->
                 <img src={solution.image} alt={solution.title} class="absolute inset-0 w-full h-full object-cover opacity-20 mix-blend-overlay" />
             </div>
          </div>
        </div>
      {/each}
    </div>
  </div>
</section>
