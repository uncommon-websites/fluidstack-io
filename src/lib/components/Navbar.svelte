<script lang="ts">
    import Logo from './Logo.svelte';
</script>

<nav class="fixed top-0 left-0 right-0 z-50 border-b border-white/10 bg-[#050505]/80 backdrop-blur-md">
    <div class="max-w-[1400px] mx-auto px-6 h-16 flex items-center justify-between">
        <a href="/" class="flex items-center">
            <Logo className="h-6 w-6" />
        </a>

        <div class="hidden md:flex items-center gap-8">
            <button class="text-sm text-gray-300 hover:text-white transition-colors flex items-center gap-1">
                Platform
                <svg width="10" height="6" viewBox="0 0 10 6" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M1 1L5 5L9 1" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
            </button>
            <a href="/gpu-clusters" class="text-sm text-gray-300 hover:text-white transition-colors">GPU Clusters</a>
            <button class="text-sm text-gray-300 hover:text-white transition-colors flex items-center gap-1">
                Resources
                <svg width="10" height="6" viewBox="0 0 10 6" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M1 1L5 5L9 1" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
            </button>
            <button class="text-sm text-gray-300 hover:text-white transition-colors flex items-center gap-1">
                About Us
                <svg width="10" height="6" viewBox="0 0 10 6" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M1 1L5 5L9 1" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
            </button>
            <a href="/careers" class="text-sm text-gray-300 hover:text-white transition-colors">Careers</a>
        </div>

        <div>
            <a href="/contact" class="inline-flex items-center justify-center px-4 py-2 text-sm font-medium text-white bg-white/10 border border-white/10 rounded hover:bg-white/20 transition-all">
                Talk to an expert
            </a>
        </div>
    </div>
</nav>