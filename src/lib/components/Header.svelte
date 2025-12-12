<script>
  export let active = "Product";
</script>

<header class="sticky top-0 z-50 w-full border-b border-gray-100 bg-white/95 backdrop-blur-sm">
  <div class="mx-auto flex h-16 max-w-7xl items-center justify-between px-4 sm:px-6 lg:px-8">
    <div class="flex items-center gap-8">
      <a href="/" class="flex items-center gap-2">
        <svg width="32" height="30" viewBox="0 0 99 92" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" clip-rule="evenodd" d="M35.5493 0C27.817 0 20.6721 4.14553 16.8059 10.875L2.92206 35.0416C-0.944067 41.7711 -0.944074 50.0622 2.92206 56.7916L16.8059 80.9583C20.6721 87.6878 27.817 91.8333 35.5493 91.8333H63.3171C71.0493 91.8333 78.1941 87.6878 82.0602 80.9583L95.9441 56.7916C99.8103 50.0622 99.8103 41.7711 95.9441 35.0416L82.0602 10.875C78.1941 4.14553 71.0493 0 63.3171 0H35.5493ZM63.3171 14.5H45.9621C43.1853 14.5 41.4503 17.5206 42.8407 19.936C47.1308 27.3885 51.431 34.8355 55.7149 42.2916C57.0036 44.5348 57.0036 47.2985 55.7149 49.5416C51.431 56.998 47.1308 64.4447 42.8407 71.8973C41.4503 74.3127 43.1853 77.3333 45.9621 77.3333H63.3171C65.8945 77.3333 68.2762 75.9515 69.5649 73.7083L83.4488 49.5416C84.7375 47.2985 84.7375 44.5348 83.4488 42.2916L69.5649 18.125C68.2762 15.8818 65.8945 14.5 63.3171 14.5Z" fill="#0A0D12"/>
        </svg>
        <span class="text-2xl font-bold tracking-tight font-sans">PARE</span>
      </a>
      
      <nav class="hidden md:flex items-center gap-6">
        {#each ["Platform", "Attribution", "Privacy", "Resources"] as item}
          <a href="#{item.toLowerCase()}" class="text-sm font-medium text-gray-600 hover:text-gray-900 transition-colors">
            {item}
          </a>
        {/each}
      </nav>
    </div>

    <div class="flex items-center gap-4">
      <a href="#login" class="text-sm font-medium text-gray-900 hover:text-gray-700">
        Log in
      </a>
      <a href="#demo" class="rounded-full bg-black px-4 py-2 text-sm font-medium text-white hover:bg-gray-800 transition-colors">
        Request Demo
      </a>
    </div>
  </div>
</header>
