<section class="py-24 bg-[#050505] border-t border-white/5">
    <div class="max-w-[1400px] mx-auto px-6">
        <div class="text-center mb-24">
            <h2 class="text-5xl md:text-7xl font-serif text-white mb-6">
                Built for Speed.<br/>
                <span class="text-gray-400">Trusted for Scale.</span>
            </h2>
            <p class="text-gray-400 max-w-xl mx-auto text-lg">
                Fluidstack gives you the control, confidence, and performance hyperscalers can't.
            </p>
        </div>

        <div class="grid grid-cols-2 md:grid-cols-4 gap-12 mb-24">
            <!-- GDPR -->
            <div class="flex flex-col items-center gap-4">
                <div class="w-20 h-20 flex items-center justify-center">
                    <svg viewBox="0 0 100 100" class="w-full h-full text-white fill-current">
                        {#each Array(12) as _, i}
                            <circle cx={50 + 35 * Math.cos(i * Math.PI / 6)} cy={50 + 35 * Math.sin(i * Math.PI / 6)} r="2" />
                        {/each}
                    </svg>
                </div>
                <span class="text-xs text-gray-500 tracking-widest flex items-center gap-1">GDPR <div class="w-3 h-3 rounded-full border border-gray-600 flex items-center justify-center text-[8px]">✓</div></span>
            </div>

            <!-- HIPAA -->
            <div class="flex flex-col items-center gap-4">
                <div class="w-20 h-20 flex items-center justify-center">
                    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="w-16 h-16 text-white">
                        <path d="M12 2L12 22M8 6C8 6 12 8 16 6M8 18C8 18 12 16 16 18" />
                        <path d="M12 2L10 4C10 4 8 5 8 8C8 11 12 12 12 12C12 12 16 13 16 16C16 19 14 20 12 22" />
                    </svg>
                </div>
                <span class="text-xs text-gray-500 tracking-widest flex items-center gap-1">HIPAA <div class="w-3 h-3 rounded-full border border-gray-600 flex items-center justify-center text-[8px]">✓</div></span>
            </div>

            <!-- ISO -->
            <div class="flex flex-col items-center gap-4">
                <div class="w-20 h-20 flex items-center justify-center relative">
                    <div class="text-3xl font-bold font-mono text-white">ISO</div>
                    <div class="absolute inset-0 border-2 border-white rounded-full opacity-20"></div>
                </div>
                <span class="text-xs text-gray-500 tracking-widest flex items-center gap-1">ISO27001 <div class="w-3 h-3 rounded-full border border-gray-600 flex items-center justify-center text-[8px]">✓</div></span>
            </div>

            <!-- SOC2 -->
            <div class="flex flex-col items-center gap-4">
                <div class="w-20 h-20 flex items-center justify-center">
                    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="w-16 h-16 text-white">
                        <path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z" />
                        <path d="M9 12l2 2 4-4" />
                    </svg>
                </div>
                <span class="text-xs text-gray-500 tracking-widest flex items-center gap-1">SOC 2 TYPE 2 <div class="w-3 h-3 rounded-full border border-gray-600 flex items-center justify-center text-[8px]">✓</div></span>
            </div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-12 border-t border-white/10 pt-12">
            <div>
                <div class="mb-4">
                    <svg class="w-6 h-6 text-white" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
                        <path d="M12 3L20 7.5V16.5L12 21L4 16.5V7.5L12 3Z" />
                        <path d="M12 12L12 21" />
                        <path d="M12 12L20 7.5" />
                        <path d="M12 12L4 7.5" />
                    </svg>
                </div>
                <h3 class="text-sm font-bold text-white mb-2">Single-Tenant by Default. <span class="font-normal text-gray-400">Your infrastructure is fully isolated at the hardware, network, and storage levels. No shared clusters. No noisy neighbors.</span></h3>
            </div>
            
            <div>
                <div class="mb-4">
                    <svg class="w-6 h-6 text-white" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
                        <path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z" />
                        <path d="M9 12l2 2 4-4" />
                    </svg>
                </div>
                <h3 class="text-sm font-bold text-white mb-2">Secure Ops, Human Support. <span class="font-normal text-gray-400">Fluidstack engineers maintain and monitor your cluster directly with secure access controls, audit logs, and 15-minute response SLAs.</span></h3>
            </div>
        </div>
    </div>
</section>