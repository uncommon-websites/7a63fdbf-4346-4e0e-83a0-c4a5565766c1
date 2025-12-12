<script>
    import { FileText, Database, Settings, Search } from 'lucide-svelte';
</script>

<section class="py-24 bg-gradient-to-b from-white via-secondary-50 to-primary-50 relative overflow-hidden">
    <!-- Decorative background elements -->
    <div class="absolute inset-0 overflow-hidden pointer-events-none">
        <div class="absolute bottom-20 right-10 w-96 h-96 bg-primary-100 rounded-full opacity-20 blur-3xl"></div>
        <div class="absolute top-40 left-20 w-72 h-72 bg-secondary-100 rounded-full opacity-30 blur-3xl"></div>
    </div>

    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 relative z-10">
        <div class="mb-20">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight max-w-4xl">
                Privacy laws blinded pharma marketers. <span class="font-semibold bg-gradient-to-r from-primary-600 to-primary-700 bg-clip-text text-transparent">PARE brings back visibility without touching patient data.</span>
            </h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
            <!-- Left: Image/Interface -->
            <div class="relative group">
                <div class="relative rounded-2xl overflow-hidden border-2 border-primary-200 bg-gradient-to-br from-primary-900 to-primary-950 aspect-[4/3] transition-all duration-500 hover:border-primary-300">
                    <img 
                        src="/generated/image-close-up-of-marketing-dashboard-showing--1765569396116-1.webp" 
                        alt="Pharmaceutical marketing attribution dashboard" 
                        class="absolute inset-0 w-full h-full object-cover opacity-30 mix-blend-overlay"
                    />
                    
                    <!-- Floating Interface Element -->
                    <div class="absolute inset-0 flex items-center justify-center p-8">
                        <div class="bg-white rounded-xl border border-primary-200 w-full max-w-md p-6 transition-all duration-500 hover:scale-105 hover:border-primary-300">
                            <div class="flex items-center gap-3 mb-4">
                                <div class="h-10 w-10 bg-gradient-to-br from-primary-600 to-primary-700 rounded-lg flex items-center justify-center text-white transition-transform duration-300 hover:scale-110">
                                    <Database size={18} />
                                </div>
                                <span class="font-medium text-gray-900">Attribution Model</span>
                            </div>
                            <div class="space-y-3">
                                <div class="flex items-center justify-between group/bar hover:scale-105 transition-transform duration-300">
                                    <span class="text-xs text-gray-600">Ad Spend Data</span>
                                    <div class="h-2 bg-gradient-to-r from-primary-100 to-primary-200 rounded-full w-24 animate-progress-1"></div>
                                </div>
                                <div class="flex items-center justify-between group/bar hover:scale-105 transition-transform duration-300">
                                    <span class="text-xs text-gray-600">Rx Volume (Zip)</span>
                                    <div class="h-2 bg-gradient-to-r from-primary-200 to-primary-300 rounded-full w-32 animate-progress-2"></div>
                                </div>
                                <div class="flex items-center justify-between group/bar hover:scale-105 transition-transform duration-300">
                                    <span class="text-xs text-gray-600">Statistical Model</span>
                                    <div class="h-2 bg-gradient-to-r from-primary-300 to-primary-400 rounded-full w-20 animate-progress-3"></div>
                                </div>
                            </div>
                            
                            <!-- Arrow indicator -->
                            <div class="absolute -left-4 top-1/2 -translate-y-1/2 bg-gradient-to-r from-primary-600 to-primary-700 rounded-full p-2 border-2 border-white animate-pulse-arrow">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Right: Features List -->
            <div class="space-y-12">
                <h3 class="text-2xl font-serif text-gray-900">
                    <span class="text-primary-600">Privacy-First Attribution</span> <br/> Built for Modern Pharma Marketing
                </h3>

                <div class="space-y-8">
                    {#each [
                        { id: '01', title: 'Aggregate data only—no patient tracking', icon: Database, color: 'primary' },
                        { id: '02', title: 'Real-time attribution insights', icon: Search, color: 'secondary' },
                        { id: '03', title: 'Weekly budget optimization', icon: Settings, color: 'primary' },
                        { id: '04', title: 'Zip-level prescription correlation', icon: FileText, color: 'secondary' }
                    ] as feature, index}
                        <div class="flex items-start gap-4 group cursor-pointer animate-feature" style="animation-delay: {index * 0.1}s">
                            <div class="flex-shrink-0 relative">
                                <div class={[
                                    'h-12 w-12 rounded-full border-2 flex items-center justify-center text-xs font-mono bg-white z-10 relative transition-all duration-300',
                                    feature.color === 'primary' ? 'border-primary-200 text-primary-600 group-hover:border-primary-600 group-hover:bg-primary-50' : 'border-secondary-200 text-secondary-600 group-hover:border-secondary-600 group-hover:bg-secondary-50'
                                ]}>
                                    {feature.id}
                                </div>
                                {#if feature.id !== '04'}
                                    <div class={[
                                        'absolute top-12 left-1/2 -translate-x-1/2 w-px h-8 -z-0 transition-all duration-300',
                                        feature.color === 'primary' ? 'bg-primary-100 group-hover:bg-primary-300' : 'bg-secondary-100 group-hover:bg-secondary-300'
                                    ]}></div>
                                {/if}
                            </div>
                            <div class="pt-2 flex-1">
                                <h4 class="text-lg text-gray-600 group-hover:text-gray-900 transition-all duration-300 font-light group-hover:translate-x-1">
                                    {feature.title}
                                </h4>
                            </div>
                        </div>
                    {/each}
                </div>
            </div>
        </div>
    </div>
</section>

<style>
    .animate-feature {
        animation: featureAppear 0.6s ease-out forwards;
        opacity: 0;
    }
    
    .animate-progress-1 {
        animation: progressGrow 1.5s ease-out forwards 0.5s;
        transform-origin: left;
        transform: scaleX(0);
    }
    
    .animate-progress-2 {
        animation: progressGrow 1.5s ease-out forwards 0.7s;
        transform-origin: left;
        transform: scaleX(0);
    }
    
    .animate-progress-3 {
        animation: progressGrow 1.5s ease-out forwards 0.9s;
        transform-origin: left;
        transform: scaleX(0);
    }
    
    .animate-pulse-arrow {
        animation: pulseArrow 2s ease-in-out infinite;
    }
    
    @keyframes featureAppear {
        from { opacity: 0; transform: translateX(-20px); }
        to { opacity: 1; transform: translateX(0); }
    }
    
    @keyframes progressGrow {
        from { transform: scaleX(0); }
        to { transform: scaleX(1); }
    }
    
    @keyframes pulseArrow {
        0%, 100% { transform: translateY(-50%) scale(1); opacity: 1; }
        50% { transform: translateY(-50%) scale(1.1); opacity: 0.8; }
    }
</style>
