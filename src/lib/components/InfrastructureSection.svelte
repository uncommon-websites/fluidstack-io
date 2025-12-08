<section class="py-24 bg-[#050505] relative overflow-hidden">
    <!-- Background glow for section -->
    <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[800px] h-[800px] bg-blue-900/10 rounded-full blur-[120px]"></div>

    <div class="max-w-[1400px] mx-auto px-6 relative z-10">
        <div class="text-center mb-20">
            <h2 class="text-5xl md:text-7xl font-serif text-white mb-6">
                Infrastructure.<br/>
                <span class="text-gray-400">Purpose-Built for AI.</span>
            </h2>
            <p class="text-gray-400 max-w-xl mx-auto text-lg">
                High performance clusters made securely available. Anytime. Anywhere.
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
            <!-- Atlas OS Card -->
            <div class="group relative rounded-xl bg-[#0A0A0A] border border-white/10 overflow-hidden min-h-[400px] p-8 hover:border-white/20 transition-all duration-300">
                <div class="absolute inset-0 bg-gradient-to-b from-blue-500/5 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
                
                <div class="relative z-10 mb-8">
                    <h3 class="text-2xl font-serif text-white mb-2">Atlas OS</h3>
                    <p class="text-gray-400 text-lg">Speed, at scale.</p>
                </div>

                <!-- UI Mockup -->
                <div class="relative z-10 bg-[#050505] border border-white/10 rounded-lg p-4 max-w-sm mx-auto shadow-2xl transform group-hover:scale-[1.02] transition-transform duration-500">
                    <div class="flex items-center justify-between mb-4 border-b border-white/5 pb-2">
                        <span class="text-xs text-gray-500 font-mono">ATLAS OS</span>
                    </div>
                    <div class="space-y-3">
                        <div class="flex items-center justify-between bg-white/5 rounded p-3">
                            <div class="flex items-center gap-2">
                                <div class="w-2 h-2 rounded-full bg-green-500"></div>
                                <span class="text-sm text-white font-mono">B200</span>
                            </div>
                            <span class="text-xs text-white/50 bg-white/10 px-2 py-1 rounded">Running</span>
                        </div>
                        <div class="flex items-center justify-between bg-white/5 rounded p-3">
                            <div class="flex items-center gap-2">
                                <div class="w-2 h-2 rounded-full bg-gray-500"></div>
                                <span class="text-sm text-white font-mono">B200</span>
                            </div>
                            <span class="text-xs text-white px-3 py-1 rounded bg-white/10 border border-white/20">Deploy</span>
                        </div>
                    </div>
                </div>

                <div class="absolute bottom-8 left-8 right-8">
                    <p class="text-sm text-gray-400 mb-4 line-clamp-2">
                        Atlas is our bare-metal OS for AI infrastructure. Fast provisioning, smooth orchestration, total ownership.
                    </p>
                    <a href="#" class="inline-flex items-center text-sm text-blue-400 hover:text-blue-300 transition-colors">
                        Explore Atlas OS 
                        <svg class="ml-2 w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>
            </div>

            <!-- Lighthouse Card -->
            <div class="group relative rounded-xl bg-[#0A0A0A] border border-white/10 overflow-hidden min-h-[400px] p-8 hover:border-white/20 transition-all duration-300">
                <div class="absolute inset-0 bg-gradient-to-b from-blue-500/5 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
                
                <div class="relative z-10 mb-8">
                    <h3 class="text-2xl font-serif text-white mb-2">Lighthouse</h3>
                    <p class="text-gray-400 text-lg">Reliable performance.</p>
                </div>

                <!-- Grid Graphic -->
                <div class="relative z-10 flex justify-center py-8">
                    <div class="grid grid-cols-10 gap-1 opacity-50">
                        {#each Array(50) as _, i}
                            <div class="w-4 h-4 border border-white/20 { [15, 28, 42].includes(i) ? 'bg-white shadow-[0_0_10px_rgba(255,255,255,0.8)]' : '' }"></div>
                        {/each}
                    </div>
                </div>

                <div class="absolute bottom-8 left-8 right-8">
                    <p class="text-sm text-gray-400 mb-4 line-clamp-2">
                        Lighthouse monitors, heals, and optimizes your workloads. It catches problems before they catch you.
                    </p>
                    <a href="#" class="inline-flex items-center text-sm text-blue-400 hover:text-blue-300 transition-colors">
                        Explore Lighthouse 
                        <svg class="ml-2 w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>
            </div>
        </div>

        <!-- GPU Clusters Card -->
        <div class="group relative rounded-xl bg-[#0A0A0A] border border-white/10 overflow-hidden p-8 hover:border-white/20 transition-all duration-300">
            <div class="absolute inset-0 bg-gradient-to-r from-purple-900/10 to-blue-900/10 opacity-50"></div>
            
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 relative z-10">
                <div class="flex flex-col justify-between">
                    <div>
                        <h3 class="text-2xl font-serif text-white mb-2">GPU Clusters</h3>
                        <p class="text-gray-400 text-lg mb-8">Rapid access.</p>
                    </div>
                    
                    <div class="mt-auto">
                        <p class="text-sm text-gray-400 mb-4 max-w-md">
                            Dedicated, high-performance GPU clusters - fully isolated, fully managed, and always available when you need them.
                        </p>
                        <a href="#" class="inline-flex items-center text-sm text-blue-400 hover:text-blue-300 transition-colors">
                            Explore GPU Clusters 
                            <svg class="ml-2 w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </a>
                    </div>
                </div>

                <!-- Table -->
                <div class="bg-black/40 border border-white/5 rounded-lg overflow-hidden backdrop-blur-sm">
                    <div class="grid grid-cols-3 gap-px bg-white/5">
                        {#each ['GB200 NVL72', 'GB200 NVL72', 'GB200 NVL72', 'GB200 NVL72', 'GB200 NVL72', 'GB200 NVL72', 'GB200 NVL72', 'GB200 NVL72', 'GB200 NVL72', 'HGX B200', 'HGX B200', 'HGX B200', 'HGX B200', 'HGX B200', 'HGX B200'] as item}
                            <div class="bg-[#0A0A0A] p-4 flex items-center gap-2">
                                <div class="w-1.5 h-1.5 rounded-full bg-green-500 shadow-[0_0_5px_rgba(34,197,94,0.5)]"></div>
                                <span class="text-xs font-mono text-gray-300">{item}</span>
                            </div>
                        {/each}
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>