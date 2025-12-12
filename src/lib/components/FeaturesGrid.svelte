<script>
    // Icons replaced with CSS shapes for pixel-perfect custom visuals
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                Built for Pharma Marketing<br />Leaders Who Need Results
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Privacy-First Architecture -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Privacy-First Architecture</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="relative">
                        <div class="h-20 w-20 border-2 border-primary-200 rounded-full flex items-center justify-center">
                            <div class="h-12 w-12 bg-primary-600 rounded-full flex items-center justify-center text-white text-xs font-bold">
                                ✓
                            </div>
                        </div>
                        <div class="absolute -top-2 -right-2 h-6 w-6 bg-green-500 rounded-full flex items-center justify-center text-white text-xs">
                            🔒
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Never touches patient data. Fully compliant with HIPAA, My Health My Data Act, and all privacy regulations. Built for the post-tracking pixel era.
                </p>
            </div>

            <!-- Multi-Channel Attribution -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Multi-Channel Attribution</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px] space-y-2">
                        <div class="h-2 bg-primary-200 rounded w-1/3 mb-4"></div>
                        {#each [{w: '90%', c: 'bg-blue-400'}, {w: '75%', c: 'bg-purple-400'}, {w: '60%', c: 'bg-green-400'}, {w: '45%', c: 'bg-yellow-400'}, {w: '30%', c: 'bg-red-400'}] as bar}
                            <div class="flex items-center gap-2">
                                <div class="h-2 w-2 rounded-full {bar.c}"></div>
                                <div class="h-1.5 {bar.c} rounded" style="width: {bar.w}"></div>
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Track performance across all digital channels—social, search, display, CTV, and more. Understand which channels drive prescriptions and optimize accordingly.
                </p>
            </div>

            <!-- Weekly Recommendations -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Weekly Recommendations</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="relative">
                        <div class="h-20 w-20 bg-white rounded-lg shadow-sm border border-gray-200 flex flex-col items-center justify-center">
                            <div class="text-xs text-gray-400 font-mono">WEEK</div>
                            <div class="text-2xl font-bold text-primary-600">3</div>
                        </div>
                        <div class="absolute -bottom-1 -right-1 h-6 w-6 bg-primary-600 rounded-full flex items-center justify-center text-white text-xs">
                            ↑
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Get actionable budget optimization recommendations delivered every week. Know exactly where to increase spend and where to pull back.
                </p>
            </div>

            <!-- Statistical Modeling -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Statistical Modeling</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="relative">
                        <!-- Tree structure visualization -->
                        <div class="flex justify-center gap-4 mb-4">
                            <div class="h-6 w-6 border border-primary-300 bg-white rounded-sm flex items-center justify-center text-[8px]">📊</div>
                            <div class="h-6 w-6 border border-primary-300 bg-white rounded-sm flex items-center justify-center text-[8px]">💊</div>
                            <div class="h-6 w-6 border border-primary-300 bg-white rounded-sm flex items-center justify-center text-[8px]">📍</div>
                        </div>
                        <div class="flex justify-center mb-4">
                            <div class="h-8 w-px bg-primary-300"></div>
                        </div>
                        <div class="flex justify-center">
                            <div class="h-8 w-8 bg-primary-600 rounded flex items-center justify-center text-white text-xs font-bold">Σ</div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Advanced statistical models correlate ad spend with prescription volumes at the zip code level, providing accurate attribution without individual tracking.
                </p>
            </div>

            <!-- Prescription Volume Integration -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Prescription Volume Integration</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px]">
                        <div class="flex justify-between mb-4">
                            <div class="text-[10px] font-bold text-gray-500">ZIP</div>
                            <div class="text-[10px] font-bold text-gray-500">Rx VOL</div>
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center justify-between">
                                <div class="text-[9px] text-gray-600">90210</div>
                                <div class="h-1.5 bg-primary-200 rounded w-3/4"></div>
                            </div>
                            <div class="flex items-center justify-between">
                                <div class="text-[9px] text-gray-600">10001</div>
                                <div class="h-1.5 bg-primary-300 rounded w-2/3"></div>
                            </div>
                            <div class="flex items-center justify-between">
                                <div class="text-[9px] text-gray-600">60614</div>
                                <div class="h-1.5 bg-primary-400 rounded w-1/2"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Seamlessly integrate with IQVIA, Symphony Health, and other prescription data providers. Analyze aggregate volumes by geography without accessing patient-level information.
                </p>
            </div>

            <!-- Ad Spend Analytics -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Ad Spend Analytics</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="grid grid-cols-3 gap-1">
                        {#each [
                            {c: 'bg-blue-400'}, {c: 'bg-blue-300'}, {c: 'bg-blue-200'},
                            {c: 'bg-purple-400'}, {c: 'bg-primary-600 flex items-center justify-center'}, {c: 'bg-green-400'},
                            {c: 'bg-yellow-400'}, {c: 'bg-red-400'}, {c: 'bg-pink-400'}
                        ] as box}
                            <div class="h-8 w-8 border border-gray-200 {box.c}">
                                {#if box.c.includes('primary-600')}
                                    <div class="h-2 w-2 bg-white rounded-full mx-auto mt-3"></div>
                                {/if}
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Automatically collect and normalize ad spend data from all your platforms. Track performance, ROI, and attribution across your entire media mix.
                </p>
            </div>
        </div>
    </div>
</section>
