<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-24">
  <div class="px-4 md:px-12 max-w-4xl mx-auto text-center mb-16">
    <div class="text-xs font-mono uppercase tracking-widest text-gray-500 mb-4">
      Integrations
    </div>
    <h2 class="font-serif text-4xl text-gray-900 mb-6">
      Establish your single source of truth
    </h2>
    <p class="text-gray-500 leading-relaxed max-w-2xl mx-auto">
      Seamless two-way integrations with back office, cashflow, portfolio, document management, and advice platforms ensure complete control of client data.
    </p>
  </div>

  <div class="px-4 md:px-12 relative">
    <!-- Connecting Line -->
    <div class="absolute top-1/2 left-0 w-full h-px bg-gray-200 -translate-y-1/2 hidden md:block"></div>

    <!-- Logos Row -->
    <div class="flex flex-wrap md:flex-nowrap items-center justify-center md:justify-between gap-8 relative z-10">
      
      <!-- Logo 1 -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-gray-400">iress</div>
      </div>

       <!-- Logo 2 -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-blue-500">intelliflo</div>
      </div>

       <!-- Center Logo (Saturn) -->
      <div class="w-24 h-24 bg-blue-900 rounded-full shadow-lg border-4 border-white flex items-center justify-center p-2 relative">
        <div class="text-white font-serif font-bold text-xs tracking-widest">SATURN</div>
        <!-- Orbit ring visual -->
        <div class="absolute inset-0 rounded-full border border-blue-700 scale-110 opacity-50"></div>
      </div>

       <!-- Logo 3 -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-green-600">T4A</div>
      </div>

       <!-- Logo 4 -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-blue-400">365</div>
      </div>

    </div>
  </div>
</SectionWrapper>
