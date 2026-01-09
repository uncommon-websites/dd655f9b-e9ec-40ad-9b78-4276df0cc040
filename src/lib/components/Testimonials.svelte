<script>
  const testimonials = [
    {
      quote: "AppInChina handled everything from legal setup to marketing execution. We launched in North America in 3 months and hit 100K users in the first quarter. Their dual-market expertise is invaluable.",
      author: "Wei Chen",
      role: "CEO, Gaming Studio",
      image: "/generated/image-chinese-entrepreneur-confidently-present-1767923527951-1.webp"
    },
    {
      quote: "We tried managing multiple vendors for our global expansion and it was chaos. AppInChina became our single point of contact, coordinating everything seamlessly. Now we can focus on product while they handle the complexity.",
      author: "Lin Zhang",
      role: "Founder, SaaS Platform",
      image: "/generated/image-young-chinese-female-founder-working-on--1767923530983-2.webp"
    },
    {
      quote: "Their localization goes beyond translation. They helped us understand cultural nuances and adapt our messaging for Western markets. Our conversion rates improved by 40% after implementing their recommendations.",
      author: "David Liu",
      role: "VP International, Mobile App",
      image: "/generated/image-chinese-tech-professional-in-casual-busi-1767923533515-3.webp"
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
        <span class="text-xs font-bold tracking-widest uppercase text-gray-500">Trusted by Innovators</span>
      </div>
      
      <h2 class="font-display font-medium text-4xl sm:text-5xl max-w-4xl leading-tight text-gray-900">
        Chinese innovation meets global markets. <span class="text-gray-500">Powered by AppInChina's expertise.</span>
      </h2>
    </div>

    <!-- Grid -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      {#each testimonials as t}
        <div class="bg-white p-8 rounded-sm shadow-sm border border-gray-100 flex flex-col h-full">
          <div class="w-12 h-12 rounded-full overflow-hidden mb-6 bg-gray-200">
            <img src={t.image} alt={t.author} class="w-full h-full object-cover grayscale" />
          </div>
          <p class="text-gray-900 text-lg font-medium leading-relaxed mb-8 flex-grow">"{t.quote}"</p>
          <div class="border-t border-gray-100 pt-4 mt-auto">
            <p class="font-bold text-xs uppercase tracking-wider text-gray-900">{t.author}</p>
            <p class="text-[10px] font-bold uppercase tracking-wider text-gray-400 mt-1">{t.role}</p>
          </div>
        </div>
      {/each}
    </div>
  </div>
</section>
