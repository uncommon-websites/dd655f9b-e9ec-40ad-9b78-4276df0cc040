<script>
  import { ArrowRight, Search, Link, Zap, Layers, Database, Mail, Phone, Calendar, BarChart, Users, MessageSquare, CheckSquare, Settings, Globe, FileText, Shield, Cloud, TrendingUp } from 'lucide-svelte';

  const features = [
    {
      title: "Strategy & Entry",
      icon: Globe,
      color: "bg-primary-100 text-primary-600",
      items: [
        { label: "Market research & analysis", icon: BarChart },
        { label: "Go-to-market strategy", icon: TrendingUp },
        { label: "Legal entity setup", icon: Shield },
        { label: "Regulatory compliance", icon: CheckSquare },
        { label: "Market positioning", icon: Search }
      ]
    },
    {
      title: "Localization",
      icon: MessageSquare,
      color: "bg-primary-100 text-primary-600",
      items: [
        { label: "Content localization", icon: FileText },
        { label: "Cultural adaptation", icon: Users },
        { label: "Brand localization", icon: Zap },
        { label: "App store optimization", icon: Settings },
        { label: "Website development", icon: Globe }
      ]
    },
    {
      title: "Marketing & Growth",
      icon: TrendingUp,
      color: "bg-primary-100 text-primary-600",
      items: [
        { label: "Paid advertising", icon: BarChart },
        { label: "Social media management", icon: MessageSquare },
        { label: "SEO & SEM", icon: Search },
        { label: "User acquisition", icon: Users },
        { label: "Analytics & reporting", icon: Database }
      ]
    },
    {
      title: "Technical Services",
      icon: Cloud,
      color: "bg-primary-100 text-primary-600",
      items: [
        { label: "Cloud infrastructure", icon: Cloud },
        { label: "Payment integration", icon: Settings },
        { label: "Subscription management", icon: Layers },
        { label: "Cross-border tax", icon: Shield },
        { label: "LLM optimization", icon: Zap }
      ]
    }
  ];
</script>

<section class="bg-gray-50 py-24 px-4 sm:px-6 lg:px-8 font-body">
  <div class="max-w-7xl mx-auto">
    <!-- Header -->
    <div class="mb-20">
      <div class="flex items-center gap-2 mb-6">
        <svg width="20" height="22" viewBox="0 0 97 105" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path opacity="0.5" d="M0.84375 29.5892V75.3785L43.791 45.7896V0L0.84375 29.5892Z" fill="black"/>
          <path opacity="0.5" d="M0.84375 75.3787V29.5891L43.791 59.1783V104.968L0.84375 75.3787Z" fill="black"/>
          <path opacity="0.5" d="M96.8438 29.5891V75.3787L53.8965 45.7895V0L96.8438 29.5891Z" fill="black"/>
          <path opacity="0.5" d="M96.8438 75.3787V29.5891L53.8965 59.1783V104.968L96.8438 75.3787Z" fill="black"/>
        </svg>
        <span class="text-xs font-bold tracking-widest uppercase text-gray-500">End-to-End Services</span>
      </div>
      
      <h2 class="font-display font-medium text-4xl sm:text-5xl max-w-4xl leading-tight text-gray-900">
        Everything you need to succeed globally. <span class="text-gray-500">From market entry strategy to technical infrastructure, we manage the complexity of international expansion.</span>
      </h2>
    </div>

    <!-- Grid -->
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-x-8 gap-y-12">
      {#each features as category}
        <div class="flex flex-col h-full">
          <h3 class="font-bold text-lg mb-6 border-b border-gray-200 pb-4">{category.title}</h3>
          
          <ul class="space-y-4 flex-grow mb-8">
            {#each category.items as item}
              <li class="flex items-center gap-3 text-sm text-gray-700">
                <div class={`w-6 h-6 rounded flex items-center justify-center shrink-0 ${category.color}`}>
                  <svelte:component this={item.icon} size={14} />
                </div>
                <span>{item.label}</span>
                {#if item.tag}
                  <span class="text-[10px] font-bold bg-gray-100 text-gray-500 px-1.5 py-0.5 rounded uppercase tracking-wider">{item.tag}</span>
                {/if}
              </li>
            {/each}
          </ul>
          
          <a href="#" class="inline-flex items-center text-sm font-bold underline decoration-1 underline-offset-4 hover:text-gray-600 transition-colors mt-auto">
            Learn more
          </a>
        </div>
      {/each}
    </div>
  </div>
</section>
