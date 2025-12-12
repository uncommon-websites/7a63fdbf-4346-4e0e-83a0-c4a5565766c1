<script>
    const partners = [
        { name: "Zip-Level Rx Data", icon: "📍" },
        { name: "Google Ads", icon: "G", color: "bg-blue-600" },
        { name: "Meta Ads", icon: "M", color: "bg-blue-500" },
        { name: "TikTok Ads", icon: "T", color: "bg-gray-900" },
        { name: "Programmatic DSPs", icon: "P", color: "bg-purple-600" },
        { name: "Connected TV", icon: "📺" },
        { name: "Search Platforms", icon: "🔍" },
        { name: "Display Networks", icon: "💻" },
        { name: "IQVIA Data", icon: "I", color: "bg-red-600" },
        { name: "Symphony Health", icon: "S", color: "bg-primary-600" },
        { name: "Your Ad Platforms", icon: "🎯" },
        { name: "Custom Data Sources", icon: "⚡" }
    ];
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16 max-w-2xl">
            <h2 class="text-3xl md:text-4xl font-serif text-gray-900 mb-6">Integrated Data Sources</h2>
            <p class="text-sm text-gray-500 leading-relaxed">
                PARE seamlessly integrates with your existing ad platforms and prescription data providers. We aggregate data from multiple sources to deliver comprehensive attribution insights while maintaining complete privacy compliance.
            </p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
            {#each partners as partner}
                <div class="flex items-center gap-4 p-4 bg-gray-50 rounded-lg hover:bg-gray-100 transition-colors cursor-default">
                    <div class={`h-8 w-8 rounded flex items-center justify-center text-white text-xs font-bold ${partner.color ? partner.color : 'bg-gray-200 text-gray-600'}`}>
                        {partner.icon}
                    </div>
                    <span class="text-sm font-medium text-gray-900">{partner.name}</span>
                </div>
            {/each}
        </div>
    </div>
</section>
