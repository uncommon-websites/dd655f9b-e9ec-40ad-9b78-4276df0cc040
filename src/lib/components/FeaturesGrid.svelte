<script>
  import { ArrowRight, Search, Link, Zap, Layers, Database, Mail, Phone, Calendar, BarChart, Users, MessageSquare, CheckSquare, Settings } from 'lucide-svelte';

  const features = [
    {
      title: "Find",
      icon: Search,
      color: "bg-orange-100 text-orange-600",
      items: [
        { label: "TAM sourcing", icon: Database },
        { label: "Contact enrichment", icon: Users },
        { label: "Company enrichment", icon: Settings },
        { label: "Intent signals", icon: BarChart, tag: "SOON" },
        { label: "Lead scoring", icon: Zap, tag: "SOON" }
      ]
    },
    {
      title: "Connect",
      icon: Link,
      color: "bg-pink-100 text-pink-600",
      items: [
        { label: "Domain & inbox purchase", icon: Mail },
        { label: "Inbox warming", icon: Zap },
        { label: "Sequencing", icon: Settings },
        { label: "Dialer", icon: Phone },
        { label: "Scheduler", icon: Calendar }
      ]
    },
    {
      title: "Sell",
      icon: Zap,
      color: "bg-green-100 text-green-600",
      items: [
        { label: "Meeting recordings", icon: MessageSquare },
        { label: "Meeting intelligence", icon: Zap },
        { label: "Smart email composer", icon: Mail },
        { label: "Smart task logging", icon: CheckSquare },
        { label: "CPQ", icon: Settings, tag: "SOON" }
      ]
    },
    {
      title: "Manage",
      icon: Layers,
      color: "bg-yellow-100 text-yellow-600",
      items: [
        { label: "CRM", icon: Database },
        { label: "Ask Reevo Copilot", icon: MessageSquare },
        { label: "Reporting", icon: BarChart },
        { label: "Workflows", icon: Zap },
        { label: "Integrations", icon: Link }
      ]
    }
  ];
</script>

<section class="bg-gray-50 py-24 px-4 sm:px-6 lg:px-8 font-body">
  <div class="max-w-7xl mx-auto">
    <!-- Header -->
    <div class="mb-20">
      <div class="flex items-center gap-2 mb-6">
        <div class="w-5 h-5 bg-black text-white flex items-center justify-center text-xs font-bold rounded-sm">R</div>
        <span class="text-xs font-bold tracking-widest uppercase text-gray-500">Built Different</span>
      </div>
      
      <h2 class="font-display font-medium text-4xl sm:text-5xl max-w-4xl leading-tight text-gray-900">
        Win more with less friction. <span class="text-gray-500">Reevo streamlines prospecting, outreach, and pipeline management so you can focus on selling—not admin work.</span>
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
