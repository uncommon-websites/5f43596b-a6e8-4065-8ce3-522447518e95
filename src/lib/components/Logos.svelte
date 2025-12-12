<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-12">
  <div class="px-4 md:px-12 flex flex-col md:flex-row items-center justify-between gap-8">
    <!-- Logos -->
    <div class="flex flex-wrap items-center gap-8 md:gap-12 grayscale opacity-70">
        <!-- Wealth Partners -->
        <div class="h-6 font-bold text-lg tracking-tight">WEALTH PARTNERS</div>
        <!-- Summit Advisory -->
        <div class="h-8 flex flex-col leading-none text-xs font-sans uppercase tracking-widest">
            <span>Summit</span>
            <span>Advisory</span>
        </div>
        <!-- Horizon -->
        <div class="h-6 font-bold text-lg lowercase italic font-sans">horizon</div>
        <!-- Apex Financial -->
        <div class="h-6 font-medium text-lg flex items-center gap-1">
            <span class="font-bold">APEX</span>
            <span class="font-light">Financial</span>
        </div>
    </div>

    <!-- Trust Text -->
    <div class="text-gray-400 text-sm font-light text-right md:text-left">
      Trusted by growing wealth management firms
    </div>
  </div>
</SectionWrapper>
