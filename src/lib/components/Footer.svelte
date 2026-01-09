<script>
    const links = {
        Services: ["Market Entry", "Localization", "Marketing", "Technical"],
        Resources: ["Case Studies", "Blog", "Market Insights", "Partner Network"],
        Company: ["About Us", "Careers", "Contact", "Press Inquiries"],
        Social: ["LinkedIn", "WeChat"]
    };
</script>

<footer class="bg-white pt-16 pb-8 px-4 sm:px-6 lg:px-8 font-body border-t border-gray-100">
    <div class="max-w-7xl mx-auto">
        <div class="grid grid-cols-2 md:grid-cols-6 gap-8 mb-16">
            <!-- Logo Column -->
            <div class="col-span-2">
                <svg width="32" height="35" viewBox="0 0 97 105" fill="none" xmlns="http://www.w3.org/2000/svg" class="mb-6">
                    <path opacity="0.5" d="M0.84375 29.5892V75.3785L43.791 45.7896V0L0.84375 29.5892Z" fill="black"/>
                    <path opacity="0.5" d="M0.84375 75.3787V29.5891L43.791 59.1783V104.968L0.84375 75.3787Z" fill="black"/>
                    <path opacity="0.5" d="M96.8438 29.5891V75.3787L53.8965 45.7895V0L96.8438 29.5891Z" fill="black"/>
                    <path opacity="0.5" d="M96.8438 75.3787V29.5891L53.8965 59.1783V104.968L96.8438 75.3787Z" fill="black"/>
                </svg>
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
                <span>© 2025 AppInChina</span>
                <span class="flex items-center gap-1"><span class="w-2 h-2 rounded-full border border-gray-300"></span> Since 2013</span>
                <span class="flex items-center gap-1"><span class="w-2 h-2 rounded-full border border-gray-300"></span> Global Partner Network</span>
            </div>
            
            <div class="flex gap-8">
                <a href="#" class="hover:text-gray-600">Privacy Policy</a>
                <a href="#" class="hover:text-gray-600">Terms of Service</a>
            </div>
        </div>
    </div>
</footer>
