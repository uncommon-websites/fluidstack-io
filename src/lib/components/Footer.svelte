<script lang="ts">
    import Logo from './Logo.svelte';
</script>

<footer class="relative bg-[#050505] pt-32 pb-12 overflow-hidden border-t border-white/5">
    <!-- Background Effects -->
    <div class="absolute inset-0 z-0 pointer-events-none">
        <div class="absolute inset-0 vertical-lines opacity-10"></div>
        <div class="absolute bottom-0 left-1/2 -translate-x-1/2 w-[1000px] h-[600px] bg-blue-900/20 rounded-full blur-[120px]"></div>
    </div>

    <div class="relative z-10 max-w-[1400px] mx-auto px-6">
        <!-- CTA Section -->
        <div class="flex flex-col items-center text-center mb-32">
            <div class="mb-8">
                <Logo className="h-8 w-8" />
            </div>
            <h2 class="text-5xl md:text-7xl font-serif text-white mb-6">
                Infrastructure for <br />
                Abundant Intelligence
            </h2>
            <p class="text-gray-400 max-w-xl mx-auto text-lg mb-10">
                We partner with top AI labs, governments, and enterprises to unlock compute at the speed of light.
            </p>
        </div>

        <!-- Links Section -->
        <div class="grid grid-cols-1 md:grid-cols-4 gap-12 mb-24">
            <div class="col-span-1">
                <Logo className="h-6 w-6" />
            </div>
            
            <div>
                <h4 class="text-sm font-medium text-white mb-6">Products</h4>
                <ul class="space-y-4">
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Atlas OS</a></li>
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Lighthouse</a></li>
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">GPU Clusters</a></li>
                </ul>
            </div>

            <div>
                <h4 class="text-sm font-medium text-white mb-6">Resources</h4>
                <ul class="space-y-4">
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Pricing</a></li>
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Documentation</a></li>
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Blog</a></li>
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Security</a></li>
                </ul>
            </div>

            <div>
                <h4 class="text-sm font-medium text-white mb-6">Company</h4>
                <ul class="space-y-4">
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">About</a></li>
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Careers</a></li>
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Contact</a></li>
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Legal</a></li>
                </ul>
            </div>
        </div>

        <!-- Bottom Bar -->
        <div class="flex flex-col md:flex-row justify-between items-center text-xs text-gray-500 border-t border-white/5 pt-8">
            <p>© 2025 Fluidstack All rights reserved.</p>
            
            <div class="flex items-center gap-4 mt-4 md:mt-0 bg-white/5 px-4 py-2 rounded-full backdrop-blur-sm border border-white/5">
                <span>We use cookies to personalize content, run ads, and analyze traffic.</span>
                <button class="bg-white text-black px-3 py-1 rounded hover:bg-gray-200 transition-colors font-medium">Okay</button>
            </div>
        </div>
    </div>
</footer>