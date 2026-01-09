<script>
  import { MessageSquare } from 'lucide-svelte';
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 font-body overflow-hidden">
  <div class="max-w-7xl mx-auto">
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 lg:gap-24 items-center">
      
      <!-- Text -->
      <div>
        <div class="flex items-center gap-2 mb-6">
            <svg width="20" height="22" viewBox="0 0 97 105" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path opacity="0.5" d="M0.84375 29.5892V75.3785L43.791 45.7896V0L0.84375 29.5892Z" fill="black"/>
              <path opacity="0.5" d="M0.84375 75.3787V29.5891L43.791 59.1783V104.968L0.84375 75.3787Z" fill="black"/>
              <path opacity="0.5" d="M96.8438 29.5891V75.3787L53.8965 45.7895V0L96.8438 29.5891Z" fill="black"/>
              <path opacity="0.5" d="M96.8438 75.3787V29.5891L53.8965 59.1783V104.968L96.8438 75.3787Z" fill="black"/>
            </svg>
            <span class="text-xs font-bold tracking-widest uppercase text-gray-500">Dual-Market Expertise</span>
        </div>

        <h2 class="font-display font-bold text-5xl sm:text-6xl uppercase leading-[0.9] mb-8 text-gray-900">
          Most agencies <br /> understand one <br /> market. We <br /> master both.
        </h2>
        
        <p class="text-gray-600 text-lg leading-relaxed mb-8">
          Since 2013, we've been the bridge between Chinese innovation and global markets. Our team combines deep understanding of Chinese business culture with on-the-ground expertise in international markets. We don't just translate—we transform.
        </p>
        
        <div class="mt-12">
            <h3 class="font-display font-bold text-xl mb-2">Your Long-Term Partner</h3>
            <p class="text-gray-500 text-sm max-w-sm">We're not a project-based agency. We become your operating partner, adapting our services as markets evolve and your business scales. From first launch to sustained growth.</p>
            
            <!-- Simple progress bar graphic -->
            <div class="mt-6 flex items-center gap-2">
                <div class="h-1 w-12 bg-primary-500 rounded-full"></div>
                <div class="h-1 w-8 bg-gray-200 rounded-full"></div>
                <div class="h-1 w-20 bg-gray-200 rounded-full"></div>
            </div>
        </div>
      </div>

      <!-- Image/UI -->
      <div class="relative">
        <div class="bg-primary-500 rounded-lg p-6 sm:p-10 shadow-2xl transform rotate-1 hover:rotate-0 transition-transform duration-500">
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <!-- Header -->
                <div class="bg-gray-50 border-b border-gray-100 p-4 flex items-center gap-3">
                    <div class="w-8 h-8 bg-primary-100 text-primary-600 rounded-full flex items-center justify-center">
                        <MessageSquare size={16} />
                    </div>
                    <div>
                        <p class="text-sm font-bold text-gray-900">Global Expansion Roadmap</p>
                        <p class="text-xs text-gray-500">North America Launch - Q1 2024</p>
                    </div>
                </div>
                
                <!-- Body -->
                <div class="p-6 space-y-6">
                    <div>
                        <p class="text-xs font-bold text-gray-900 mb-2">Phase 1: Foundation (Weeks 1-4)</p>
                        <ul class="space-y-2">
                            <li class="flex items-start gap-2 text-xs text-gray-600">
                                <span class="w-1 h-1 rounded-full bg-primary-500 mt-1.5 shrink-0"></span>
                                <span><span class="font-bold text-gray-900">Legal Setup:</span> Delaware C-Corp registration, EIN, bank account</span>
                            </li>
                            <li class="flex items-start gap-2 text-xs text-gray-600">
                                <span class="w-1 h-1 rounded-full bg-primary-500 mt-1.5 shrink-0"></span>
                                <span><span class="font-bold text-gray-900">Compliance:</span> Privacy policy, terms of service, GDPR/CCPA readiness</span>
                            </li>
                            <li class="flex items-start gap-2 text-xs text-gray-600">
                                <span class="w-1 h-1 rounded-full bg-primary-500 mt-1.5 shrink-0"></span>
                                <span><span class="font-bold text-gray-900">Localization:</span> App store listings, UI/UX adaptation, content translation</span>
                            </li>
                        </ul>
                    </div>
                    
                    <div class="bg-gray-50 p-4 rounded border border-gray-100">
                        <p class="text-xs font-bold text-gray-900 mb-1">Phase 2: Launch (Weeks 5-8)</p>
                        <p class="text-xs text-gray-600 mt-2">Soft launch with paid acquisition campaigns, influencer partnerships, and PR outreach. Target: 10K users, $50K MRR by end of Q1.</p>
                        
                        <div class="mt-3 flex items-center gap-2">
                            <div class="flex-1 bg-gray-200 h-2 rounded-full overflow-hidden">
                                <div class="bg-primary-500 h-full w-3/4"></div>
                            </div>
                            <span class="text-[10px] font-bold text-gray-500">75%</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
      </div>

    </div>
  </div>
</section>
