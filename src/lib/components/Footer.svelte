<script>
    const links = {
        Products: ["Find", "Connect", "Sell", "Manage"],
        Platform: ["Pricing", "Blog", "Product Tour", "Login"],
        Company: ["About us", "Careers", "Startup Program", "Press & Partner Inquiries"],
        Social: ["LinkedIn", "X/Twitter"]
    };
</script>

<footer class="bg-white pt-16 pb-8 px-4 sm:px-6 lg:px-8 font-body border-t border-gray-100">
    <div class="max-w-7xl mx-auto">
        <div class="grid grid-cols-2 md:grid-cols-6 gap-8 mb-16">
            <!-- Logo Column -->
            <div class="col-span-2">
                <div class="w-8 h-8 bg-black text-white flex items-center justify-center font-display font-bold text-xl rounded-sm mb-6">R</div>
            </div>
            
            <!-- Link Columns -->
            {#each Object.entries(links) as [category, items]}
                <div>
                    <h4 class="font-bold text-xs text-gray-900 uppercase tracking-wider mb-4">{category}</h4>
                    <ul class="space-y-3">
                        {#each items as item}
                            <li>
                                <a href="#" class="text-sm text-gray-500 hover:text-black transition-colors">{item}</a>
                            </li>
                        {/each}
                    </ul>
                </div>
            {/each}
        </div>
        
        <!-- Bottom Bar -->
        <div class="flex flex-col md:flex-row justify-between items-center pt-8 border-t border-gray-100 text-[10px] text-gray-400 uppercase tracking-wider font-medium gap-4">
            <div class="flex gap-8">
                <span>© 2025 Reevo Inc.</span>
                <span class="flex items-center gap-1"><span class="w-2 h-2 rounded-full border border-gray-300"></span> SOC2 Compliant</span>
                <span class="flex items-center gap-1"><span class="w-2 h-2 rounded-full border border-gray-300"></span> AICPA SOC Trusted</span>
            </div>
            
            <div class="flex gap-8">
                <a href="#" class="hover:text-gray-600">Privacy Policy</a>
                <a href="#" class="hover:text-gray-600">Terms of Service</a>
            </div>
        </div>
    </div>
</footer>
