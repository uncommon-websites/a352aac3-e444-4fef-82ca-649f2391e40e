<script lang="ts">
  let selectedColor = 'white';
</script>

<section class="bg-[#f9f9f7] py-24 px-6">
  <div class="max-w-[1200px] mx-auto text-center">
    <h2 class="text-[40px] font-light text-gray-900 mb-16">
      Five sizes. <span class="text-gray-400">Tons of possibility.</span>
    </h2>

    <div class="mb-8">
      <h3 class="text-2xl font-normal mb-2">One bedroom</h3>
      <p class="text-gray-500 text-sm">The one and only for everything.</p>
    </div>

    <!-- 3D Model Placeholder -->
    <div class="relative w-full h-[400px] bg-white rounded-xl mb-8 flex items-center justify-center overflow-hidden shadow-sm">
      <div class="absolute inset-0 flex items-center justify-between px-4">
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m15 18-6-6 6-6"/></svg>
        </button>
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
        </button>
      </div>
      <img src="https://images.unsplash.com/photo-1512917774080-9991f1c4c750?q=80&w=2070&auto=format&fit=crop" class="h-[80%] object-contain" alt="House Model" />
    </div>

    <!-- Controls -->
    <div class="flex justify-center gap-4 mb-8">
      <button class="w-8 h-8 rounded-full bg-[#dbeafe] border-2 border-blue-500 ring-2 ring-offset-2 ring-blue-200"></button>
      <button class="w-8 h-8 rounded-full bg-[#f3f4f6]"></button>
      <button class="w-8 h-8 rounded-full bg-[#374151]"></button>
      <button class="w-8 h-8 rounded-full bg-[#4b5563]"></button>
    </div>

    <div class="flex justify-center gap-8 text-sm text-gray-600 mb-4 border-b border-gray-200 pb-4 inline-flex mx-auto w-auto px-12">
      <span>540 sq. ft.</span>
      <span>1 bedroom</span>
      <span>1 bath</span>
    </div>

    <p class="text-xs text-gray-500 mb-8">
      Starting at <span class="font-bold text-gray-900">$170,000</span> plus installation.<br>
      Financing options available. ⓘ
    </p>

    <div class="flex justify-center gap-4">
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors text-left">
        <span class="block text-[10px] text-gray-500">Want to see more?</span>
        <span class="text-blue-600">Explore the one bedroom</span>
      </button>
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z"/><polyline points="3.27 6.96 12 12.01 20.73 6.96"/><line x1="12" y1="22.08" x2="12" y2="12"/></svg>
        Configure in 3D ->
      </button>
    </div>
  </div>
</section>
