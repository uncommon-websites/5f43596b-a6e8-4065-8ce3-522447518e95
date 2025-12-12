<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
  import SolutionBlock from './SolutionBlock.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="">
  <div class="px-4 md:px-12">
    <div class="py-16 text-center">
      <h2 class="font-sans text-4xl text-gray-900">Our solutions</h2>
    </div>

    <!-- Block 1 -->
    <SolutionBlock
      label="AI Document Extraction"
      title="Extract data from any document"
      description="Upload tax returns, bank statements, investment reports, or any client document. Verlo's AI instantly extracts names, addresses, account numbers, balances, and other key data with industry-leading accuracy."
    >
      <!-- Visual for Block 1: Files -->
      <div class="relative w-full h-full flex items-center justify-center">
        <!-- Central Hub -->
        <div class="w-16 h-16 bg-white shadow-lg rounded-lg flex items-center justify-center z-10 border border-gray-100">
           <div class="w-8 h-8 bg-[var(--color-primary-600)] rounded-sm"></div>
        </div>
        
        <!-- Connected Files -->
        <div class="absolute top-1/4 left-1/4 bg-white p-3 shadow rounded border border-gray-100 animate-pulse">
            <div class="w-8 h-10 bg-[var(--color-primary-100)] rounded flex items-center justify-center text-[10px] font-bold text-[var(--color-primary-700)]">.PDF</div>
            <div class="mt-1 text-[10px] text-center">Tax Return</div>
        </div>
        <div class="absolute top-1/4 right-1/4 bg-white p-3 shadow rounded border border-gray-100">
            <div class="w-8 h-10 bg-[var(--color-primary-800)] rounded flex items-center justify-center text-[10px] font-bold text-white">.PDF</div>
            <div class="mt-1 text-[10px] text-center">Bank Stmt</div>
        </div>
        <div class="absolute bottom-1/4 left-1/3 bg-white p-3 shadow rounded border border-gray-100">
            <div class="w-8 h-10 bg-[var(--color-primary-500)] rounded flex items-center justify-center text-[10px] font-bold text-white">.PDF</div>
            <div class="mt-1 text-[10px] text-center">Brokerage</div>
        </div>
         <div class="absolute bottom-1/4 right-1/3 bg-white p-3 shadow rounded border border-gray-100">
            <div class="w-8 h-10 bg-gray-200 rounded flex items-center justify-center text-[10px] font-bold text-gray-600">.DOCX</div>
            <div class="mt-1 text-[10px] text-center">Estate Plan</div>
        </div>
        
        <!-- Connecting Lines (Simplified) -->
        <svg class="absolute inset-0 w-full h-full pointer-events-none opacity-20" viewBox="0 0 400 300">
            <path d="M100 100 L200 150 M300 100 L200 150 M150 220 L200 150 M250 220 L200 150" stroke="currentColor" stroke-width="1" stroke-dasharray="4 4" />
        </svg>
      </div>
    </SolutionBlock>

    <!-- Block 2 -->
    <SolutionBlock
      label="Automated Form Filling"
      title="Fill forms in seconds, not hours"
      description="Stop copying data field by field. Verlo intelligently maps extracted information to your PDF forms and compliance documents. One click fills everything—from account applications to KYC forms to beneficiary designations."
      reversed={true}
    >
      <!-- Visual for Block 2: UI Card -->
      <div class="bg-white rounded-lg shadow-xl p-6 w-3/4 max-w-sm border border-gray-100">
        <div class="flex items-center space-x-3 mb-4">
            <div class="w-8 h-8 rounded-full bg-gray-300 overflow-hidden">
                <img src="https://i.pravatar.cc/100?img=5" alt="Avatar" class="w-full h-full object-cover" />
            </div>
            <div class="text-xs text-gray-500">Sarah Johnson • New Client</div>
        </div>
        <h4 class="font-sans text-xl mb-4">Account Application Form</h4>
        <div class="space-y-3 mb-6">
            <div class="flex justify-between text-xs">
                <span class="text-gray-500">Name:</span>
                <span class="font-medium">Sarah Johnson</span>
            </div>
            <div class="flex justify-between text-xs">
                <span class="text-gray-500">SSN:</span>
                <span class="font-medium">***-**-4892</span>
            </div>
            <div class="flex justify-between text-xs">
                <span class="text-gray-500">Address:</span>
                <span class="font-medium">123 Main St...</span>
            </div>
            <div class="text-[10px] text-[var(--color-primary-600)] flex items-center gap-1">
                <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                Auto-filled from tax return
            </div>
        </div>
        <button class="w-full bg-[var(--color-primary-600)] text-white py-2 rounded text-sm font-medium flex items-center justify-center space-x-2 hover:bg-[var(--color-primary-700)] transition-colors">
            <span>Generate PDF</span>
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
        </button>
      </div>
    </SolutionBlock>

    <!-- Block 3 -->
    <SolutionBlock
      label="Smart Meeting Notes"
      title="Capture every client conversation"
      description="Never miss important details again. Verlo listens to your client meetings and automatically generates structured notes with action items, key decisions, and relevant data points—ready to add to your CRM or compliance files."
    >
       <!-- Visual for Block 3: Report -->
       <div class="bg-white rounded shadow-lg p-8 w-2/3 max-w-xs border border-gray-100 relative">
          <div class="flex justify-between items-center mb-6 border-b pb-2">
              <div class="font-bold text-xs">Meeting Notes</div>
              <div class="w-4 h-4 bg-[var(--color-primary-600)] rounded-full"></div>
          </div>
          <div class="mb-4">
              <h5 class="font-bold text-sm">Client Discovery Call</h5>
              <div class="text-[10px] text-gray-400">Michael Chen • Jan 15, 2025</div>
          </div>
          <div class="space-y-2 text-[8px] text-gray-500 leading-relaxed">
              <p><strong>Key Points:</strong> Client is 52, planning retirement at 65. Current 401(k) balance $850K. Concerned about market volatility.</p>
              <p><strong>Action Items:</strong> Review risk tolerance questionnaire. Prepare diversification proposal. Schedule follow-up for Jan 22.</p>
              <p><strong>Next Steps:</strong> Client will send recent statements and beneficiary forms.</p>
          </div>
       </div>
    </SolutionBlock>
  </div>
</SectionWrapper>
