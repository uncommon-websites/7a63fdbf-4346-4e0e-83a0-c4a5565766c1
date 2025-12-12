<script>
  // No imports needed as we use inline SVGs for specific styling control
</script>

<section class="relative flex flex-col items-center justify-start pt-20 pb-32 overflow-hidden">
  <!-- Content -->
  <div class="z-10 mx-auto max-w-4xl px-4 text-center mb-16">
    <h1 class="mb-6 text-5xl md:text-6xl lg:text-7xl font-serif text-gray-900 leading-tight">
      Marketing Attribution Without Patient Data
    </h1>
    <p class="mx-auto mb-10 max-w-2xl text-lg text-gray-600 leading-relaxed">
      Real-time attribution and weekly budget optimization for pharma brands using aggregate data and statistical modeling—fully compliant with HIPAA and privacy laws
    </p>
    
    <div class="flex justify-center">
        <div class="relative group">
            <!-- Decorative brackets/corners could be added here if needed, but simple button for now -->
            <button class="relative rounded-full bg-black px-8 py-3 text-base font-medium text-white hover:bg-gray-800 transition-all">
                Request a Demo
            </button>
            <!-- Decorative corners -->
            <div class="absolute -top-2 -left-2 h-4 w-4 border-t-2 border-l-2 border-black"></div>
            <div class="absolute -bottom-2 -right-2 h-4 w-4 border-b-2 border-r-2 border-black"></div>
        </div>
    </div>
  </div>

  <!-- Hero Image & Dashboard Interface -->
  <div class="relative w-full max-w-7xl mx-auto px-4">
    <div class="relative aspect-[21/9] w-full overflow-hidden rounded-lg shadow-2xl bg-gradient-to-br from-gray-50 to-gray-100">
      <img 
        src="/generated/image-professional-pharmaceutical-marketing-te-1765569393254-0.webp" 
        alt="Pharmaceutical marketing analytics" 
        class="h-full w-full object-cover opacity-20"
      />
      
      <!-- Overlay Dashboard Preview -->
      <div class="absolute inset-0 flex items-center justify-center p-8">
        <div class="w-full max-w-4xl rounded-xl bg-white p-6 shadow-2xl animate-fade-in-up">
            <!-- Dashboard Header -->
            <div class="flex items-center justify-between mb-6 pb-4 border-b border-gray-100">
                <div>
                    <div class="text-xs font-mono uppercase tracking-widest text-gray-400 mb-1">Campaign Performance</div>
                    <div class="text-lg font-semibold text-gray-900">Weekly Attribution Report</div>
                </div>
                <div class="flex items-center gap-2">
                    <div class="px-3 py-1 bg-primary-50 text-primary-700 text-xs font-medium rounded-full">
                        Live Data
                    </div>
                </div>
            </div>
            
            <!-- Dashboard Metrics -->
            <div class="grid grid-cols-4 gap-4">
                <div class="bg-gray-50 rounded-lg p-4">
                    <div class="text-xs text-gray-500 mb-1">Total Ad Spend</div>
                    <div class="text-2xl font-bold text-gray-900">$2.4M</div>
                    <div class="text-xs text-green-600 mt-1">↑ 12% vs last week</div>
                </div>
                <div class="bg-gray-50 rounded-lg p-4">
                    <div class="text-xs text-gray-500 mb-1">Attributed Rx Volume</div>
                    <div class="text-2xl font-bold text-gray-900">8,432</div>
                    <div class="text-xs text-green-600 mt-1">↑ 8.3% lift</div>
                </div>
                <div class="bg-gray-50 rounded-lg p-4">
                    <div class="text-xs text-gray-500 mb-1">Cost per Rx</div>
                    <div class="text-2xl font-bold text-gray-900">$284</div>
                    <div class="text-xs text-gray-500 mt-1">Optimized</div>
                </div>
                <div class="bg-gray-50 rounded-lg p-4">
                    <div class="text-xs text-gray-500 mb-1">Top Zip Codes</div>
                    <div class="text-2xl font-bold text-gray-900">247</div>
                    <div class="text-xs text-primary-600 mt-1">High performers</div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</section>

<style>
    .animate-fade-in-up {
        animation: fadeInUp 0.8s ease-out forwards;
    }
    @keyframes fadeInUp {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
    }
</style>
