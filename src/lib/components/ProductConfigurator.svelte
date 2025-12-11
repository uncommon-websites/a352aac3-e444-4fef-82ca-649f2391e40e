<script lang="ts">
  let selectedColor = 'walnut';
</script>

<section class="bg-[#f9f9f7] py-24 px-6">
  <div class="max-w-[1200px] mx-auto text-center">
    <h2 class="text-[40px] font-light text-gray-900 mb-16">
      Every piece is unique. <span class="text-gray-400">Custom-made for you.</span>
    </h2>

    <div class="mb-8">
      <h3 class="text-2xl font-normal mb-2">Dining Collection</h3>
      <p class="text-gray-500 text-sm">Tables, chairs, and credenzas crafted to your specifications.</p>
    </div>

    <!-- Featured Image -->
    <div class="relative w-full h-[400px] bg-white rounded-xl mb-8 flex items-center justify-center overflow-hidden shadow-sm">
      <div class="absolute inset-0 flex items-center justify-between px-4">
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m15 18-6-6 6-6"/></svg>
        </button>
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
        </button>
      </div>
      <img src="/generated/image-elegant-wooden-dining-chairs-around-a-ha-1765468727054-6.webp" class="h-[90%] w-[90%] object-cover rounded" alt="Dining furniture" />
    </div>

    <!-- Wood Species Options -->
    <div class="flex justify-center gap-4 mb-8">
      <button class="w-8 h-8 rounded-full bg-[#8B4513] border-2 border-primary-600 ring-2 ring-offset-2 ring-primary-200" title="Walnut"></button>
      <button class="w-8 h-8 rounded-full bg-[#DEB887]" title="Oak"></button>
      <button class="w-8 h-8 rounded-full bg-[#D2691E]" title="Cherry"></button>
      <button class="w-8 h-8 rounded-full bg-[#654321]" title="Mahogany"></button>
    </div>

    <div class="flex justify-center gap-8 text-sm text-gray-600 mb-4 border-b border-gray-200 pb-4 inline-flex mx-auto w-auto px-12">
      <span>Traditional joinery</span>
      <span>Rare wood species</span>
      <span>Custom dimensions</span>
    </div>

    <p class="text-xs text-gray-500 mb-8">
      Pricing varies by design, materials, and dimensions.<br>
      Schedule a consultation to discuss your project.
    </p>

    <div class="flex justify-center gap-4">
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors text-left">
        <span class="block text-[10px] text-gray-500">Want to see more?</span>
        <span class="text-primary-600">Explore the collection</span>
      </button>
      <button class="px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="17 8 12 3 7 8"/><line x1="12" x2="12" y1="3" y2="15"/></svg>
        Start a commission ->
      </button>
    </div>
  </div>
</section>
