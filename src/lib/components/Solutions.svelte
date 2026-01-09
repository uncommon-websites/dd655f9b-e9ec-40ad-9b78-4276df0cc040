<script>
  import { ArrowRight } from 'lucide-svelte';

  const solutions = [
    {
      tag: "STRATEGY",
      title: "ENTER NEW MARKETS WITH CONFIDENCE",
      description: "We handle market research, regulatory compliance, legal entity setup, and go-to-market strategy. Launch in new territories with a clear roadmap and compliant operations from day one.",
      color: "bg-primary-50",
      accent: "bg-primary-500",
      textAccent: "text-primary-600",
      image: "https://images.unsplash.com/photo-1551288049-bebda4e38f71?q=80&w=2940&auto=format&fit=crop"
    },
    {
      tag: "LOCALIZATION",
      title: "SPEAK YOUR CUSTOMERS' LANGUAGE",
      description: "Beyond translation, we adapt your brand, content, and user experience for local markets. From app store optimization to culturally-resonant messaging, we make your product feel native.",
      color: "bg-primary-50",
      accent: "bg-primary-500",
      textAccent: "text-primary-600",
      image: "https://images.unsplash.com/photo-1516321318423-f06f85e504b3?q=80&w=2940&auto=format&fit=crop"
    },
    {
      tag: "MARKETING",
      title: "ACQUIRE USERS AT SCALE",
      description: "Paid advertising, social media, SEO, and growth marketing executed by teams who understand both your home market and your target markets. Drive sustainable user acquisition and engagement.",
      color: "bg-primary-50",
      accent: "bg-primary-500",
      textAccent: "text-primary-600",
      image: "https://images.unsplash.com/photo-1460925895917-afdab827c52f?q=80&w=2426&auto=format&fit=crop"
    },
    {
      tag: "TECHNICAL",
      title: "BUILD ON SOLID INFRASTRUCTURE",
      description: "Cloud architecture, payment integration, subscription management, and cross-border tax compliance. We partner with AWS, Azure, RevenueCat, and leading providers to ensure your technical foundation scales.",
      color: "bg-primary-50",
      accent: "bg-primary-500",
      textAccent: "text-primary-600",
      image: "https://images.unsplash.com/photo-1558494949-ef010cbdcc31?q=80&w=2940&auto=format&fit=crop"
    }
  ];
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 font-body">
  <div class="max-w-7xl mx-auto">
    <!-- Header -->
    <div class="mb-24">
      <div class="flex items-center gap-2 mb-6">
        <svg width="20" height="22" viewBox="0 0 97 105" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path opacity="0.5" d="M0.84375 29.5892V75.3785L43.791 45.7896V0L0.84375 29.5892Z" fill="black"/>
          <path opacity="0.5" d="M0.84375 75.3787V29.5891L43.791 59.1783V104.968L0.84375 75.3787Z" fill="black"/>
          <path opacity="0.5" d="M96.8438 29.5891V75.3787L53.8965 45.7895V0L96.8438 29.5891Z" fill="black"/>
          <path opacity="0.5" d="M96.8438 75.3787V29.5891L53.8965 59.1783V104.968L96.8438 75.3787Z" fill="black"/>
        </svg>
        <span class="text-xs font-bold tracking-widest uppercase text-gray-500">The Solution: AppInChina</span>
      </div>
      
      <h2 class="font-display font-medium text-4xl sm:text-5xl max-w-4xl leading-tight text-gray-900">
        One partner for your entire global expansion. <br />
        <span class="text-gray-500">From strategy to execution. Managed services, not just software.</span>
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
