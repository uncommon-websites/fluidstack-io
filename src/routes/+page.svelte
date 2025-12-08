<script lang="ts">
    import Navbar from '$lib/components/Navbar.svelte';
    import Hero from '$lib/components/Hero.svelte';
    import NewsSection from '$lib/components/NewsSection.svelte';
    import InfrastructureSection from '$lib/components/InfrastructureSection.svelte';
    import TrustSection from '$lib/components/TrustSection.svelte';
    import LogoGrid from '$lib/components/LogoGrid.svelte';
    import Footer from '$lib/components/Footer.svelte';
</script>

<div class="bg-[#050505] min-h-screen text-white selection:bg-blue-500/30">
    <Navbar />
    <main>
        <Hero />
        <NewsSection />
        <InfrastructureSection />
        <LogoGrid /> <!-- Wait, looking at screenshot, LogoGrid is after TrustSection? No, it's "The stack behind leading AI companies" which is near the bottom before Footer but after TrustSection -->
        <!-- Actually in screenshot:
        1. Hero
        2. News (Anthropic/Poolside)
        3. Infrastructure (Atlas/Lighthouse/GPU)
        4. Built for Speed (TrustSection)
        5. The stack behind leading AI companies (LogoGrid)
        6. Footer
        -->
        <TrustSection />
        <LogoGrid />
    </main>
    <Footer />
</div>

