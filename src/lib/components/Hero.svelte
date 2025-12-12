<script>
  // No imports needed as we use inline SVGs for specific styling control
</script>

<section class="relative flex flex-col items-center justify-start pt-20 pb-32 overflow-hidden bg-gradient-to-b from-primary-50 via-white to-secondary-50">
  <!-- Decorative background elements -->
  <div class="absolute inset-0 overflow-hidden pointer-events-none">
    <div class="absolute top-20 left-10 w-72 h-72 bg-primary-100 rounded-full opacity-30 blur-3xl animate-float"></div>
    <div class="absolute top-40 right-20 w-96 h-96 bg-secondary-100 rounded-full opacity-20 blur-3xl animate-float-delayed"></div>
  </div>

  <!-- Content -->
  <div class="z-10 mx-auto max-w-4xl px-4 text-center mb-16 animate-fade-in">
    <h1 class="mb-6 text-5xl md:text-6xl lg:text-7xl font-serif text-gray-900 leading-tight">
      Marketing Attribution <span class="text-primary-600">Without Patient Data</span>
    </h1>
    <p class="mx-auto mb-10 max-w-2xl text-lg text-gray-600 leading-relaxed">
      Real-time attribution and weekly budget optimization for pharma brands using aggregate data and statistical modeling—fully compliant with HIPAA and privacy laws
    </p>
    
    <div class="flex justify-center">
        <div class="relative group">
            <button class="relative rounded-full bg-gradient-to-r from-primary-600 to-primary-700 px-8 py-3 text-base font-medium text-white transition-all duration-300 hover:scale-105 hover:from-primary-700 hover:to-primary-800">
                Request a Demo
            </button>
            <!-- Decorative corners with brand colors -->
            <div class="absolute -top-2 -left-2 h-4 w-4 border-t-2 border-l-2 border-primary-600 transition-all duration-300 group-hover:border-primary-700"></div>
            <div class="absolute -bottom-2 -right-2 h-4 w-4 border-b-2 border-r-2 border-primary-600 transition-all duration-300 group-hover:border-primary-700"></div>
        </div>
    </div>
  </div>

  <!-- Hero Image & Dashboard Interface -->
  <div class="relative w-full max-w-7xl mx-auto px-4 animate-fade-in-up">
    <div class="relative aspect-[21/9] w-full overflow-hidden rounded-2xl border-2 border-primary-100 bg-gradient-to-br from-primary-50 via-white to-secondary-50">
      <img 
        src="/generated/image-professional-pharmaceutical-marketing-te-1765569393254-0.webp" 
        alt="Pharmaceutical marketing analytics" 
        class="h-full w-full object-cover opacity-20"
      />
      
      <!-- Overlay Dashboard Preview -->
      <div class="absolute inset-0 flex items-center justify-center p-8">
        <div class="w-full max-w-4xl rounded-xl bg-white border border-primary-100 p-6 backdrop-blur-sm animate-dashboard-appear hover:scale-[1.02] transition-transform duration-500">
            <!-- Dashboard Header -->
            <div class="flex items-center justify-between mb-6 pb-4 border-b border-gradient-to-r from-primary-100 via-gray-100 to-secondary-100">
                <div>
                    <div class="text-xs font-mono uppercase tracking-widest text-primary-600 mb-1">Campaign Performance</div>
                    <div class="text-lg font-semibold text-gray-900">Weekly Attribution Report</div>
                </div>
                <div class="flex items-center gap-2">
                    <div class="px-3 py-1 bg-gradient-to-r from-primary-50 to-primary-100 text-primary-700 text-xs font-medium rounded-full border border-primary-200 animate-pulse-subtle">
                        Live Data
                    </div>
                </div>
            </div>
            
            <!-- Dashboard Metrics -->
            <div class="grid grid-cols-4 gap-4">
                <div class="bg-gradient-to-br from-gray-50 to-primary-50 rounded-lg p-4 border border-primary-100 hover:border-primary-300 transition-all duration-300 hover:scale-105 cursor-pointer animate-metric-1">
                    <div class="text-xs text-gray-500 mb-1">Total Ad Spend</div>
                    <div class="text-2xl font-bold text-gray-900">$2.4M</div>
                    <div class="text-xs text-primary-600 mt-1">↑ 12% vs last week</div>
                </div>
                <div class="bg-gradient-to-br from-gray-50 to-secondary-50 rounded-lg p-4 border border-secondary-100 hover:border-secondary-300 transition-all duration-300 hover:scale-105 cursor-pointer animate-metric-2">
                    <div class="text-xs text-gray-500 mb-1">Attributed Rx Volume</div>
                    <div class="text-2xl font-bold text-gray-900">8,432</div>
                    <div class="text-xs text-primary-600 mt-1">↑ 8.3% lift</div>
                </div>
                <div class="bg-gradient-to-br from-gray-50 to-primary-50 rounded-lg p-4 border border-primary-100 hover:border-primary-300 transition-all duration-300 hover:scale-105 cursor-pointer animate-metric-3">
                    <div class="text-xs text-gray-500 mb-1">Cost per Rx</div>
                    <div class="text-2xl font-bold text-gray-900">$284</div>
                    <div class="text-xs text-gray-500 mt-1">Optimized</div>
                </div>
                <div class="bg-gradient-to-br from-gray-50 to-secondary-50 rounded-lg p-4 border border-secondary-100 hover:border-secondary-300 transition-all duration-300 hover:scale-105 cursor-pointer animate-metric-4">
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
    .animate-fade-in {
        animation: fadeIn 0.8s ease-out forwards;
    }
    
    .animate-fade-in-up {
        animation: fadeInUp 1s ease-out forwards;
    }
    
    .animate-dashboard-appear {
        animation: dashboardAppear 1.2s ease-out forwards;
    }
    
    .animate-float {
        animation: float 8s ease-in-out infinite;
    }
    
    .animate-float-delayed {
        animation: float 10s ease-in-out infinite 2s;
    }
    
    .animate-pulse-subtle {
        animation: pulseSubtle 2s ease-in-out infinite;
    }
    
    .animate-metric-1 {
        animation: metricAppear 0.6s ease-out forwards 0.2s;
        opacity: 0;
    }
    
    .animate-metric-2 {
        animation: metricAppear 0.6s ease-out forwards 0.4s;
        opacity: 0;
    }
    
    .animate-metric-3 {
        animation: metricAppear 0.6s ease-out forwards 0.6s;
        opacity: 0;
    }
    
    .animate-metric-4 {
        animation: metricAppear 0.6s ease-out forwards 0.8s;
        opacity: 0;
    }
    
    @keyframes fadeIn {
        from { opacity: 0; }
        to { opacity: 1; }
    }
    
    @keyframes fadeInUp {
        from { opacity: 0; transform: translateY(30px); }
        to { opacity: 1; transform: translateY(0); }
    }
    
    @keyframes dashboardAppear {
        from { opacity: 0; transform: translateY(20px) scale(0.95); }
        to { opacity: 1; transform: translateY(0) scale(1); }
    }
    
    @keyframes float {
        0%, 100% { transform: translate(0, 0) scale(1); }
        50% { transform: translate(20px, -20px) scale(1.1); }
    }
    
    @keyframes pulseSubtle {
        0%, 100% { opacity: 1; }
        50% { opacity: 0.8; }
    }
    
    @keyframes metricAppear {
        from { opacity: 0; transform: translateY(10px); }
        to { opacity: 1; transform: translateY(0); }
    }
</style>
