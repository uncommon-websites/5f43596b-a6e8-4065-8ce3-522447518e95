<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-20 md:py-24">
  <div class="px-4 md:px-12 max-w-4xl mx-auto text-center">
    <h1 class="font-serif text-5xl md:text-7xl text-gray-900 mb-6 leading-tight">
      Unlock your advice <br/> firm's potential
    </h1>
    <p class="text-gray-500 text-lg md:text-xl max-w-2xl mx-auto mb-10 leading-relaxed font-light">
      Enhance client experience and boost your team's productivity. Augment your current processes and empower your team to deliver excellence at scale.
    </p>
    <a href="#" class="inline-flex items-center px-6 py-3 bg-[var(--color-primary-blue)] text-white font-medium rounded hover:opacity-90 transition-opacity">
      Get in touch with us <span class="ml-2">→</span>
    </a>
  </div>

  <div class="mt-16 md:mt-20 px-4 md:px-12">
    <div class="relative w-full aspect-[16/9] md:aspect-[21/9] rounded-lg overflow-hidden bg-gray-200">
      <!-- Placeholder for image -->
      <img 
        src="https://images.unsplash.com/photo-1556761175-5973dc0f32e7?ixlib=rb-4.0.3&auto=format&fit=crop&w=2000&q=80" 
        alt="Meeting in office" 
        class="w-full h-full object-cover"
      />
      
      <!-- Video Overlay Button -->
      <div class="absolute inset-0 flex items-center justify-center">
        <button class="flex items-center space-x-3 bg-black/80 backdrop-blur-sm text-white px-5 py-3 rounded hover:bg-black transition-colors">
          <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24">
            <path d="M8 5v14l11-7z" />
          </svg>
          <span class="text-sm font-medium">Watch 'The state of AI in advice' film</span>
        </button>
      </div>
    </div>
  </div>
</SectionWrapper>
