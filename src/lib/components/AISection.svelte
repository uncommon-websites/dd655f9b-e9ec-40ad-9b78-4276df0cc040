<script>
  import { MessageSquare } from 'lucide-svelte';
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 font-body overflow-hidden">
  <div class="max-w-7xl mx-auto">
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 lg:gap-24 items-center">
      
      <!-- Text -->
      <div>
        <div class="flex items-center gap-2 mb-6">
            <div class="w-5 h-5 bg-black text-white flex items-center justify-center text-xs font-bold rounded-sm">R</div>
            <span class="text-xs font-bold tracking-widest uppercase text-gray-500">The Dream Team of Intelligence</span>
        </div>

        <h2 class="font-display font-bold text-5xl sm:text-6xl uppercase leading-[0.9] mb-8 text-gray-900">
          Your "AI Tools" <br /> are guessing. <br /> Reevo actually <br /> knows.
        </h2>
        
        <p class="text-gray-600 text-lg leading-relaxed mb-8">
          You can't bolt AI onto a web of point tools and expect magic. When your richest data is stranded in point solutions, your AI is working with a blindfold on. Reevo captures every bit of first party data across the revenue cycle for better results.
        </p>
        
        <div class="mt-12">
            <h3 class="font-display font-bold text-xl mb-2">Meet your GTM Co-Pilot</h3>
            <p class="text-gray-500 text-sm max-w-sm">Ask Reevo anything about your pipeline, deal health, objections, or next steps. Stop digging for information, it doesn't just summarize; it reasons across your entire dataset.</p>
            
            <!-- Simple progress bar graphic -->
            <div class="mt-6 flex items-center gap-2">
                <div class="h-1 w-12 bg-orange-500 rounded-full"></div>
                <div class="h-1 w-8 bg-gray-200 rounded-full"></div>
                <div class="h-1 w-20 bg-gray-200 rounded-full"></div>
            </div>
        </div>
      </div>

      <!-- Image/UI -->
      <div class="relative">
        <div class="bg-orange-500 rounded-lg p-6 sm:p-10 shadow-2xl transform rotate-1 hover:rotate-0 transition-transform duration-500">
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <!-- Chat Header -->
                <div class="bg-gray-50 border-b border-gray-100 p-4 flex items-center gap-3">
                    <div class="w-8 h-8 bg-orange-100 text-orange-600 rounded-full flex items-center justify-center">
                        <MessageSquare size={16} />
                    </div>
                    <div>
                        <p class="text-sm font-bold text-gray-900">The best seller on your team in these types of situations is:</p>
                        <div class="flex items-center gap-1">
                             <div class="w-4 h-4 bg-gray-200 rounded-full flex items-center justify-center text-[8px]">M</div>
                             <p class="text-xs text-gray-500">Michael Zhao</p>
                        </div>
                    </div>
                </div>
                
                <!-- Chat Body -->
                <div class="p-6 space-y-6">
                    <div>
                        <p class="text-xs font-bold text-gray-900 mb-2">Michael's objection handling strength lies in his structured approach:</p>
                        <ul class="space-y-2">
                            <li class="flex items-start gap-2 text-xs text-gray-600">
                                <span class="w-1 h-1 rounded-full bg-orange-500 mt-1.5 shrink-0"></span>
                                <span><span class="font-bold text-gray-900">Acknowledge</span> the concern sincerely.</span>
                            </li>
                            <li class="flex items-start gap-2 text-xs text-gray-600">
                                <span class="w-1 h-1 rounded-full bg-orange-500 mt-1.5 shrink-0"></span>
                                <span><span class="font-bold text-gray-900">Empathize</span> without rushing to pitch.</span>
                            </li>
                            <li class="flex items-start gap-2 text-xs text-gray-600">
                                <span class="w-1 h-1 rounded-full bg-orange-500 mt-1.5 shrink-0"></span>
                                <span><span class="font-bold text-gray-900">Reframe</span> around measurable outcomes.</span>
                            </li>
                             <li class="flex items-start gap-2 text-xs text-gray-600">
                                <span class="w-1 h-1 rounded-full bg-orange-500 mt-1.5 shrink-0"></span>
                                <span><span class="font-bold text-gray-900">Reinforce</span> with real-world examples or success stories.</span>
                            </li>
                        </ul>
                    </div>
                    
                    <div class="bg-gray-50 p-4 rounded border border-gray-100">
                        <p class="text-xs font-bold text-gray-900 mb-1">Example 1:</p>
                        <p class="text-[10px] font-bold text-gray-500 uppercase mb-2">Objection:</p>
                        <p class="text-xs text-gray-600 italic">"We don't have budget for this right now."</p>
                        
                        <p class="text-[10px] font-bold text-gray-500 uppercase mt-3 mb-2">Talk Track:</p>
                        <p class="text-xs text-gray-600">"I completely understand, budgets are tight at this point in the year. Out of curiosity, when you run next quarter's budget, do you typically account for cost savings from efficiency gains? The reason I ask is because many of our clients ended up funding the purchase through what they saved in the first few months of..."</p>
                    </div>
                </div>
            </div>
        </div>
      </div>

    </div>
  </div>
</section>
