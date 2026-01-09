<script>
  import { ArrowRight, Play, Search, User, Menu } from 'lucide-svelte';
</script>

<div class="w-full font-body">
  <!-- Top Banner -->
  <div class="bg-primary-50 text-xs sm:text-sm py-2 px-4 text-center font-medium flex justify-center items-center gap-2">
    <span>Trusted by leading Chinese apps expanding globally since 2013</span>
    <span class="hidden sm:inline">|</span>
    <a href="#" class="hover:underline flex items-center gap-1">Our story <ArrowRight size={12} /></a>
  </div>

  <!-- Main Navigation -->
  <nav class="bg-white border-b border-gray-100 py-4 px-6 md:px-10 flex items-center justify-between sticky top-0 z-50">
    <!-- Logo -->
    <div class="flex items-center gap-3">
      <svg width="32" height="35" viewBox="0 0 97 105" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path opacity="0.5" d="M0.84375 29.5892V75.3785L43.791 45.7896V0L0.84375 29.5892Z" fill="black"/>
        <path opacity="0.5" d="M0.84375 75.3787V29.5891L43.791 59.1783V104.968L0.84375 75.3787Z" fill="black"/>
        <path opacity="0.5" d="M96.8438 29.5891V75.3787L53.8965 45.7895V0L96.8438 29.5891Z" fill="black"/>
        <path opacity="0.5" d="M96.8438 75.3787V29.5891L53.8965 59.1783V104.968L96.8438 75.3787Z" fill="black"/>
      </svg>
      <span class="font-display font-bold text-xl tracking-tight hidden sm:block">AppInChina</span>
    </div>

    <!-- Desktop Menu -->
    <div class="hidden md:flex items-center gap-8 text-sm font-medium text-gray-600">
      <a href="#" class="hover:text-black">Services</a>
      <a href="#" class="hover:text-black">Case Studies</a>
      <a href="#" class="hover:text-black">Partners</a>
      <a href="#" class="hover:text-black">About</a>
      <a href="#" class="hover:text-black">Resources</a>
    </div>

    <!-- Actions -->
    <div class="flex items-center gap-4">
      <a href="#" class="text-sm font-medium hover:text-black hidden sm:block">Contact</a>
      <a href="#" class="bg-black text-white text-sm font-medium px-4 py-2 rounded-sm hover:bg-gray-800 transition-colors">Get started</a>
      <button class="md:hidden text-gray-600">
        <Menu size={24} />
      </button>
    </div>
  </nav>
</div>
