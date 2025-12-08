<script lang="ts">
    import { onMount } from 'svelte';
    
    // Logos for the bottom section
    const logos = [
        { name: 'poolside', src: '/logos/poolside.svg' }, // Placeholder paths
        { name: 'NVIDIA', src: '/logos/nvidia.svg' },
        { name: 'Meta', src: '/logos/meta.svg' },
        { name: 'Cognition', src: '/logos/cognition.svg' },
        { name: 'Black Forest Labs', src: '/logos/blackforest.svg' }
    ];
</script>

<section class="relative min-h-screen flex flex-col pt-32 overflow-hidden">
    <!-- Background Effects -->
    <div class="absolute inset-0 z-0">
        <!-- Vertical Lines -->
        <div class="absolute inset-0 vertical-lines opacity-20"></div>
        
        <!-- Blue Glows -->
        <div class="absolute top-1/4 left-1/4 w-[500px] h-[500px] bg-blue-500/20 rounded-full blur-[120px] mix-blend-screen"></div>
        <div class="absolute top-1/3 right-1/4 w-[600px] h-[600px] bg-blue-600/10 rounded-full blur-[100px] mix-blend-screen"></div>
        <div class="absolute bottom-0 left-0 right-0 h-1/2 bg-gradient-to-t from-[#050505] to-transparent"></div>
    </div>

    <div class="relative z-10 max-w-[1400px] mx-auto px-6 flex-grow flex flex-col justify-center">
        <div class="max-w-4xl">
            <h1 class="text-6xl md:text-8xl font-serif leading-[1.1] tracking-tight text-white mb-8">
                Infrastructure for <br />
                Abundant Intelligence
            </h1>
            <p class="text-lg md:text-xl text-gray-300 max-w-2xl mb-10 font-light leading-relaxed">
                We partner with top AI labs, governments, and enterprises to unlock compute at the speed of light.
            </p>
            
            <a href="/roles" class="inline-flex items-center justify-center px-6 py-3 text-sm font-medium text-white bg-white/10 border border-white/10 rounded hover:bg-white/20 transition-all backdrop-blur-sm">
                Open roles
            </a>
        </div>
    </div>

    <!-- Logos Section -->
    <div class="relative z-10 w-full border-t border-white/5 bg-black/20 backdrop-blur-sm mt-auto">
        <div class="max-w-[1400px] mx-auto px-6 py-12">
            <p class="text-center text-sm text-gray-400 mb-8">Powering today's most ambitious teams</p>
            <div class="flex flex-wrap justify-between items-center gap-8 opacity-80 grayscale hover:grayscale-0 transition-all duration-500">
                <!-- Poolside -->
                <div class="h-6 text-white font-bold text-xl flex items-center gap-2">
                    <div class="w-6 h-6 border-2 border-white rounded-full"></div> poolside
                </div>

                <!-- NVIDIA -->
                <div class="h-6 flex items-center gap-2 text-white font-bold text-xl">
                    <div class="w-6 h-4 bg-white"></div> NVIDIA
                </div>

                <!-- Meta -->
                <div class="h-6 flex items-center gap-2 text-white font-bold text-xl">
                    <span class="text-2xl">∞</span> Meta
                </div>

                <!-- Cognition -->
                <div class="h-6 flex items-center gap-2 text-white font-bold text-xl">
                    <div class="w-6 h-6 border border-dashed border-white rounded-full animate-spin-slow"></div> Cognition
                </div>

                <!-- Black Forest Labs -->
                <div class="h-6 flex items-center gap-2 text-white font-bold text-sm">
                    <div class="w-6 h-6 border border-white rotate-45"></div> Black <br> Forest Labs
                </div>
            </div>
        </div>
    </div>
</section>

<style>
    .animate-spin-slow {
        animation: spin 10s linear infinite;
    }
    @keyframes spin {
        from { transform: rotate(0deg); }
        to { transform: rotate(360deg); }
    }
</style>