<script>
  import { ArrowRight, Play, Search, User, Menu } from 'lucide-svelte';
</script>

<div class="w-full font-body">
  <!-- Top Banner -->
  <div class="bg-cyan-100 text-xs sm:text-sm py-2 px-4 text-center font-medium flex justify-center items-center gap-2">
    <span>Reevo raises $20M from Khosla Ventures & Kleiner Perkins</span>
    <span class="hidden sm:inline">|</span>
    <a href="#" class="hover:underline flex items-center gap-1">Learn more <ArrowRight size={12} /></a>
  </div>

  <!-- Main Navigation -->
  <nav class="bg-white border-b border-gray-100 py-4 px-6 md:px-10 flex items-center justify-between sticky top-0 z-50">
    <!-- Logo -->
    <div class="flex items-center gap-2">
      <div class="w-8 h-8 bg-black text-white flex items-center justify-center font-display font-bold text-xl rounded-sm">R</div>
      <span class="font-display font-bold text-xl tracking-tight hidden sm:block">Reevo</span>
    </div>

    <!-- Desktop Menu -->
    <div class="hidden md:flex items-center gap-8 text-sm font-medium text-gray-600">
      <a href="#" class="hover:text-black">Products</a>
      <a href="#" class="hover:text-black">Pricing</a>
      <a href="#" class="hover:text-black">Team</a>
      <a href="#" class="hover:text-black">Company</a>
      <a href="#" class="hover:text-black">Resources</a>
    </div>

    <!-- Actions -->
    <div class="flex items-center gap-4">
      <a href="#" class="text-sm font-medium hover:text-black hidden sm:block">Login</a>
      <a href="#" class="bg-black text-white text-sm font-medium px-4 py-2 rounded-sm hover:bg-gray-800 transition-colors">Get started</a>
      <button class="md:hidden text-gray-600">
        <Menu size={24} />
      </button>
    </div>
  </nav>
</div>
