<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} withBorderTop={true} className="py-6">
  <nav class="flex items-center justify-between px-4 md:px-12">
    <!-- Logo -->
    <div class="font-serif text-2xl font-medium tracking-wide text-primary-600">
      Verlo
    </div>

    <!-- Links -->
    <div class="hidden md:flex items-center space-x-8 text-sm text-gray-600 font-medium">
      <a href="#" class="hover:text-primary-600 transition-colors">Product</a>
      <a href="#" class="hover:text-primary-600 transition-colors">Security</a>
      <a href="#" class="hover:text-primary-600 transition-colors">Customers</a>
      <a href="#" class="hover:text-primary-600 transition-colors">About</a>
    </div>

    <!-- Action -->
    <div>
      <a href="#" class="inline-block px-6 py-2 bg-primary-600 hover:bg-primary-700 text-white text-sm font-medium rounded transition-colors">
        Get started
      </a>
    </div>
  </nav>
</SectionWrapper>
