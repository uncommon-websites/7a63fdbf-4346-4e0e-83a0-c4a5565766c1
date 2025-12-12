<script>
    import { Check, ArrowRight } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                How PARE Delivers<br />Privacy-Compliant Attribution
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Card 1: Real-Time Attribution -->
            <div class="group">
                <div class="mb-6 bg-primary-950 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                    <!-- Mock Interface -->
                    <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3 border-b pb-2">
                            <div class="h-2 w-2 rounded-full bg-primary-500"></div>
                            <span class="text-[10px] font-mono text-gray-500">Live Attribution Tracking</span>
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center gap-2 text-xs text-primary-700">
                                <Check size={12} /> <span class="text-gray-600">Processing data...</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Collecting ad spend</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Analyzing Rx volumes</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Computing attribution</span>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Real-Time Attribution</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Track campaign performance in real-time using aggregate data. Our statistical models correlate ad spend with zip-level prescription volumes to show what's working—without ever touching patient information.
                </p>
            </div>

            <!-- Card 2: Weekly Optimization -->
            <div class="group">
                <div class="mb-6 bg-primary-950 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="text-[10px] text-gray-500 mb-2">Budget Optimization Recommendations</div>
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-600 rounded flex items-center justify-center text-white text-[8px]">W</div>
                            <span class="text-[10px] text-gray-400">Week of Jan 15, 2024</span>
                        </div>
                        <div class="space-y-2 border-t pt-2">
                            <div class="grid grid-cols-3 gap-2 text-[8px] text-gray-400 font-medium">
                                <div>Channel</div>
                                <div class="text-right">Current</div>
                                <div class="text-right">Recommended</div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-blue-400 rounded-sm"></div> Social</div>
                                <div class="text-right text-gray-600">$450K</div>
                                <div class="text-right text-green-600">↑ $520K</div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-purple-400 rounded-sm"></div> Display</div>
                                <div class="text-right text-gray-600">$380K</div>
                                <div class="text-right text-red-600">↓ $310K</div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-green-400 rounded-sm"></div> Search</div>
                                <div class="text-right text-gray-600">$290K</div>
                                <div class="text-right text-green-600">↑ $340K</div>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Weekly Budget Optimization</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Receive actionable recommendations every week on how to reallocate your budget across channels. Our models identify which campaigns drive prescriptions and suggest optimal spend allocation.
                </p>
            </div>

            <!-- Card 3: Statistical Modeling -->
            <div class="group">
                <div class="mb-6 bg-primary-950 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-600 rounded flex items-center justify-center text-white text-[8px]">M</div>
                            <span class="text-[10px] text-gray-500">Statistical Model Output</span>
                        </div>
                        <div class="text-[9px] text-gray-600 mb-3 leading-relaxed">
                            Correlation analysis complete. Identified high-performing zip codes and channel effectiveness.
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-primary-500 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Model Confidence: 94%</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-primary-400 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Zip Codes Analyzed: 3,247</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Statistical Modeling</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Advanced statistical models analyze the relationship between ad spend and prescription volumes at the zip code level. Get accurate attribution without individual patient tracking.
                </p>
            </div>
        </div>
    </div>
</section>
