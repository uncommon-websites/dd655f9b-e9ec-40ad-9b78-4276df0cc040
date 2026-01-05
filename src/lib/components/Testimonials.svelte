<script>
  const testimonials = [
    {
      quote: "Reevo has cut down the tool sprawl that used to slow us down. We can finally get rid of a dozen other apps, everything we need is finally in one place.",
      author: "Alex Zh.",
      role: "CRO, SaaS",
      image: "https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?q=80&w=2787&auto=format&fit=crop"
    },
    {
      quote: "We closed a deal two weeks faster because Reevo auto-generated follow ups we hadn't even thought of. That's the kind of impact that shows up in the numbers, not just my calendar.",
      author: "Lisa D.",
      role: "Founder, Stealth Co.",
      image: "https://images.unsplash.com/photo-1494790108377-be9c29b29330?q=80&w=2787&auto=format&fit=crop"
    },
    {
      quote: "Any team member can just open Reevo, ask it a question in plain English, and instantly get the context they need; from call notes to next steps. I don't have to repeat myself in Slack or email, and nothing slips through the cracks.",
      author: "Gil",
      role: "Head of Sales, Vercal",
      image: "https://images.unsplash.com/photo-1500648767791-00dcc994a43e?q=80&w=2787&auto=format&fit=crop"
    }
  ];
</script>

<section class="bg-gray-50 py-24 px-4 sm:px-6 lg:px-8 font-body">
  <div class="max-w-7xl mx-auto">
    <!-- Header -->
    <div class="mb-20">
      <div class="flex items-center gap-2 mb-6">
        <div class="w-5 h-5 bg-black text-white flex items-center justify-center text-xs font-bold rounded-sm">R</div>
        <span class="text-xs font-bold tracking-widest uppercase text-gray-500">Customers Love Reevo</span>
      </div>
      
      <h2 class="font-display font-medium text-4xl sm:text-5xl max-w-4xl leading-tight text-gray-900">
        Built by outsiders. <span class="text-gray-500">Loved by insiders. <br /> Feared by dinosaurs.</span>
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
