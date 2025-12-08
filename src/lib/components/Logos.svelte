<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-12">
  <div class="px-4 md:px-12 flex flex-col md:flex-row items-center justify-between gap-8">
    <!-- Logos -->
    <div class="flex flex-wrap items-center gap-8 md:gap-12 grayscale opacity-70">
        <!-- Cooper Parry -->
        <div class="h-6 font-bold text-lg tracking-tighter">COOPER PARRY</div>
        <!-- Cullen Wealth -->
        <div class="h-8 flex flex-col leading-none text-xs font-serif uppercase tracking-widest">
            <span>Cullen</span>
            <span>Wealth</span>
        </div>
        <!-- Progeny -->
        <div class="h-6 font-bold text-lg lowercase italic font-serif">progeny</div>
        <!-- Insight -->
        <div class="h-6 font-medium text-lg italic flex items-center gap-1">
            <span class="not-italic font-bold">((</span>insight
        </div>
    </div>

    <!-- Trust Text -->
    <div class="text-gray-400 text-sm font-light text-right md:text-left">
      Trusted by over 350 leading advice firms
    </div>
  </div>
</SectionWrapper>
