<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
  import SolutionBlock from './SolutionBlock.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="">
  <div class="px-4 md:px-12">
    <div class="py-16 text-center">
      <h2 class="font-serif text-4xl text-gray-900">Our solutions</h2>
    </div>

    <!-- Block 1 -->
    <SolutionBlock
      label="Data Capture Solutions"
      title="Discover client insights"
      description="Turn unstructured data, meetings & documents into actionable insights that build trust. Unify everything into a single source of truth through deep data integrations for your back-office systems and platforms."
    >
      <!-- Visual for Block 1: Files -->
      <div class="relative w-full h-full flex items-center justify-center">
        <!-- Central Hub -->
        <div class="w-16 h-16 bg-white shadow-lg rounded-lg flex items-center justify-center z-10 border border-gray-100">
           <div class="w-8 h-8 bg-blue-600 rounded-sm"></div>
        </div>
        
        <!-- Connected Files -->
        <div class="absolute top-1/4 left-1/4 bg-white p-3 shadow rounded border border-gray-100 animate-pulse">
            <div class="w-8 h-10 bg-blue-100 rounded flex items-center justify-center text-[10px] font-bold text-blue-700">.PDF</div>
            <div class="mt-1 text-[10px] text-center">Portfolio</div>
        </div>
        <div class="absolute top-1/4 right-1/4 bg-white p-3 shadow rounded border border-gray-100">
            <div class="w-8 h-10 bg-blue-800 rounded flex items-center justify-center text-[10px] font-bold text-white">.CSV</div>
            <div class="mt-1 text-[10px] text-center">Financial</div>
        </div>
        <div class="absolute bottom-1/4 left-1/3 bg-white p-3 shadow rounded border border-gray-100">
            <div class="w-8 h-10 bg-blue-500 rounded flex items-center justify-center text-[10px] font-bold text-white">.DOCX</div>
            <div class="mt-1 text-[10px] text-center">Fund</div>
        </div>
         <div class="absolute bottom-1/4 right-1/3 bg-white p-3 shadow rounded border border-gray-100">
            <div class="w-8 h-10 bg-gray-200 rounded flex items-center justify-center text-[10px] font-bold text-gray-600">.TXT</div>
            <div class="mt-1 text-[10px] text-center">Policy</div>
        </div>
        
        <!-- Connecting Lines (Simplified) -->
        <svg class="absolute inset-0 w-full h-full pointer-events-none opacity-20" viewBox="0 0 400 300">
            <path d="M100 100 L200 150 M300 100 L200 150 M150 220 L200 150 M250 220 L200 150" stroke="currentColor" stroke-width="1" stroke-dasharray="4 4" />
        </svg>
      </div>
    </SolutionBlock>

    <!-- Block 2 -->
    <SolutionBlock
      label="Workflow Solutions"
      title="Streamline manual tasks"
      description="From suitability letters to annual reviews, release your team from admin to focus exclusively on client value delivery. Create a seamless digital ecosystem where your technology operates in perfect harmony, scaling effortlessly with your growing business."
      reversed={true}
    >
      <!-- Visual for Block 2: UI Card -->
      <div class="bg-white rounded-lg shadow-xl p-6 w-3/4 max-w-sm border border-gray-100">
        <div class="flex items-center space-x-3 mb-4">
            <div class="w-8 h-8 rounded-full bg-gray-300 overflow-hidden">
                <img src="https://i.pravatar.cc/100?img=5" alt="Avatar" class="w-full h-full object-cover" />
            </div>
            <div class="text-xs text-gray-500">Fiona • Fact Find meeting</div>
        </div>
        <h4 class="font-serif text-xl mb-4">Meeting with Fiona</h4>
        <div class="space-y-2 mb-6">
            <div class="h-2 bg-gray-100 rounded w-full"></div>
            <div class="h-2 bg-gray-100 rounded w-5/6"></div>
            <div class="h-2 bg-gray-100 rounded w-4/6"></div>
        </div>
        <button class="w-full bg-blue-700 text-white py-2 rounded text-sm font-medium flex items-center justify-center space-x-2">
            <span>Handover to Paraplanner</span>
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
        </button>
      </div>
    </SolutionBlock>

    <!-- Block 3 -->
    <SolutionBlock
      label="Guardian Compliance Suite"
      title="Enable compliance excellence"
      description="Reinvent compliance from burden to advantage with intelligent risk management technology. Automate file checks & meeting observations to gain complete visibility of your firm's regulatory adherence across every client interaction."
    >
       <!-- Visual for Block 3: Report -->
       <div class="bg-white rounded shadow-lg p-8 w-2/3 max-w-xs border border-gray-100 relative">
          <div class="flex justify-between items-center mb-6 border-b pb-2">
              <div class="font-bold text-xs">MW Wealth</div>
              <div class="w-4 h-4 bg-black rounded-full"></div>
          </div>
          <div class="mb-4">
              <h5 class="font-bold text-sm">Suitability report</h5>
              <div class="text-[10px] text-gray-400">Created for 120 advice firms by Saturn</div>
          </div>
          <div class="space-y-2 text-[8px] text-gray-500 leading-relaxed">
              <p>This is a income associated with the partnership in a London law firm, earning approximately £150,000 monthly.</p>
              <p>James highlighted the importance of managing expenses, including a £5,000 monthly spend and a £200 car lease.</p>
          </div>
       </div>
    </SolutionBlock>
  </div>
</SectionWrapper>
