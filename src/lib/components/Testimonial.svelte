<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-24">
  <div class="px-4 md:px-12 mb-16 text-center">
    <h2 class="font-serif text-4xl text-gray-900">Empower your whole team</h2>
  </div>

  <div class="px-4 md:px-12 max-w-5xl mx-auto">
    <div class="flex flex-col md:flex-row gap-12 items-center">
      <!-- Image -->
      <div class="w-full md:w-1/3">
        <div class="aspect-[3/4] bg-gray-200 rounded-lg overflow-hidden relative">
          <img 
            src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" 
            alt="Alan Smith" 
            class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500"
          />
          <div class="absolute bottom-4 left-4 text-white text-xs font-bold uppercase tracking-widest opacity-80">
            Capital
          </div>
        </div>
      </div>

      <!-- Quote -->
      <div class="w-full md:w-2/3">
        <blockquote class="font-light text-xl md:text-2xl text-gray-500 leading-relaxed mb-8">
          "The value is in strategy, it's in thoughtful planning, it's in project management, it's in solving problems. <span class="text-gray-900">Saturn lets us focus on delivering that for our clients</span>"
        </blockquote>
        
        <div class="border-t border-gray-200 border-dashed pt-6">
          <div class="font-serif text-lg font-bold text-gray-900">Alan Smith</div>
          <div class="text-sm text-gray-500">CEO</div>
          <div class="text-sm text-gray-500">Capital Partners</div>
        </div>
      </div>
    </div>
  </div>
</SectionWrapper>
