<script>
  import Header from '$lib/components/Header.svelte';
  import Hero from '$lib/components/Hero.svelte';
  import FeaturesGrid from '$lib/components/FeaturesGrid.svelte';
  import ProblemSection from '$lib/components/ProblemSection.svelte';
  import Solutions from '$lib/components/Solutions.svelte';
  import Testimonials from '$lib/components/Testimonials.svelte';
  import AISection from '$lib/components/AISection.svelte';
  import BigTestimonial from '$lib/components/BigTestimonial.svelte';
  import FooterCTA from '$lib/components/FooterCTA.svelte';
  import Footer from '$lib/components/Footer.svelte';
</script>

<svelte:head>
  <title>AppInChina - Global Expansion Services for Chinese Apps & SaaS</title>
  <meta name="description" content="End-to-end global expansion services for Chinese apps, games, and SaaS. From strategy to execution, we handle the complexity so you can focus on growth." />
</svelte:head>

<div class="min-h-screen bg-white">
  <Header />
  <main>
    <Hero />
    <FeaturesGrid />
    <ProblemSection />
    <Solutions />
    <Testimonials />
    <AISection />
    <BigTestimonial />
    <FooterCTA />
  </main>
  <Footer />
</div>

