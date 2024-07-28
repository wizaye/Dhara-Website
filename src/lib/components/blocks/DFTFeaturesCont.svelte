<script lang="ts">
    import Heart from '@/img/heart.svelte';
    import Trophy from '@/img/trophy.svelte';
    import Checkbox from '@/img/checkbox.svelte';
    import Rocket from '@/img/rocket.svelte';
    import Graph from '@/img/graph.svelte';
    import ArrowSec from '@/img/arrowsec.svelte';
    import L1 from '@/img/line1.svelte'
</script>

<div class="overflow-hidden px-20 py-10 max-md:px-5">
  <div class="flex gap-5 max-md:flex-col">
    <div class="flex flex-col w-[36%] max-md:ml-0 max-md:w-full">
      <div
        class="flex flex-col self-stretch my-auto max-md:mt-10 max-md:max-w-full"
      >
        <div
          class="text-4xl font-medium leading-10 text-zinc-800 max-md:max-w-full"
        >
          Unlocking New <br />Opportunities with DFT
        </div>
        <div
          class="mt-5 text-lg font-light leading-7 text-neutral-500 max-md:max-w-full"
        >
          Deep Financing Tokens (DFT) could revolutionize supply chain finance
          for banks, expanding services, reaching new clients, and driving
          fintech innovation.
        </div>
      </div>
    </div>
    <div class="flex flex-col ml-5 w-[64%] max-md:ml-0 max-md:w-full">
      <div class="grow max-md:mt-10 max-md:max-w-full">
        <div class="flex gap-5 max-md:flex-col">
          <div class="flex flex-col w-[5%] max-md:ml-0 max-md:w-full">
            <L1 />
          </div>
          <div class="flex flex-col ml-5 w-[83%] max-md:ml-0 max-md:w-full">
            <div class="flex flex-col grow max-md:mt-1.5 max-md:max-w-full">
              <div class="max-md:max-w-full">
                <div class="flex gap-5 max-md:flex-col">
                  <div class="flex flex-col w-6/12 max-md:ml-0 max-md:w-full">
                    <div
                      class="flex flex-col grow items-start pb-20 mt-20 max-md:mt-10"
                    >
                    <div
                    class="flex flex-col justify-center p-3.5 mt-5 bg-white rounded-xl border border-solid shadow-lg border-black border-opacity-10 gap-5" 
                  >
                  <div class="flex w-10 h-10 p-x-2.5 p-y-2.5 justify-center items-center rounded-md bg-fafa" style="background-color: #EBF5EB;">
                    <div class="w-full aspect-square">
                      <Rocket />
                    </div>
                  </div>
                    <div
                      class="mt-6 text-lg font-medium leading-6 text-zinc-800"
                    >
                    Innovative Financing Solutions
                    </div>
                    <div
                      class="mt-2 text-xs font-light leading-5 text-neutral-500"
                    >
                    DFT lets banks offer blockchain-based financing to 
                    SMEs, providing a flexible alternative to traditional 
                    credit lines.
                    </div>
                  </div>
                  <div
                        class="flex flex-col justify-center p-3.5 mt-5 bg-white rounded-xl border border-solid shadow-lg border-black border-opacity-10 gap-5"  
                      >
                      <div class="flex w-10 h-10 p-x-2.5 p-y-2.5 justify-center items-center rounded-md bg-fafa" style="background-color: #F8E5E6;">
                        <div class="w-full aspect-square">
                          <Graph />
                        </div>
                      </div>
                        <div
                          class="mt-6 text-lg font-medium leading-6 text-zinc-800"
                        >
                        Enhanced Risk Management
                        </div>
                        <div
                          class="mt-2 text-xs font-light leading-5 text-neutral-500"
                        >
                        DFT's transparent ledger and smart contracts 
                        enhance banks' risk management, ensuring
                        security with clear visibility and immutable records.
                        </div>
                      </div>
                      <div
                        class="flex flex-col justify-center p-3.5 mt-5 bg-white rounded-xl border border-solid shadow-lg border-black border-opacity-10 gap-5"
                      >
                      <div class="flex w-10 h-10 p-x-2.5 p-y-2.5 justify-center items-center rounded-md bg-fafa" style="background-color: #F2EEFE;">
                        <div class="w-full aspect-square">
                          <ArrowSec />
                        </div>
                      </div>
                        <div
                          class="mt-6 text-lg font-medium leading-6 text-zinc-800"
                        >
                        Expanding Clientele Base
                        </div>
                        <div
                          class="mt-2 text-xs font-light leading-5 text-neutral-500"
                        >
                        DFT adoption helps banks attract new clients, 
                        especially underserved SMEs, expanding market 
                        share and revenue streams.
                        </div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="flex flex-col ml-5 w-6/12 max-md:ml-0 max-md:w-full"
                  >
                    <div class="flex flex-col max-md:mt-6">
                      <div
                        class="flex flex-col justify-center p-3.5 bg-white rounded-xl border border-solid shadow-lg border-black border-opacity-10 gap-5"
                      >
                      <div class="flex w-10 h-10 p-x-2.5 p-y-2.5 justify-center items-center rounded-md bg-fafa" style="background-color: #FAF0E6;">
                        <div class="w-full aspect-square">
                          <Heart />
                        </div>
                      </div>
                        <div
                          class="mt-6 text-lg font-medium leading-6 text-zinc-800"
                        >
                          Enhancing Client Relationships
                        </div>
                        <div
                          class="mt-2 text-xs font-light leading-5 text-neutral-500"
                        >
                          DFT solutions help banks strengthen relationships with
                          clients by offering advanced tools for effective
                          supply chain financing management.
                        </div>
                      </div>
                      <div
                        class="flex flex-col justify-center p-3.5 mt-5 bg-white rounded-xl border border-solid shadow-lg border-black border-opacity-10 gap-5"
                      >
                      <div class="flex w-10 h-10 p-x-2.5 p-y-2.5 justify-center items-center rounded-md bg-fafa" style="background-color: #E6F6F3;">
                        <div class="w-full aspect-square">
                          <Trophy />
                        </div>
                      </div>
                        <div
                          class="mt-6 text-lg font-medium leading-6 text-zinc-800"
                        >
                          Competitive Edge in Fintech
                        </div>
                        <div
                          class="mt-2 text-xs font-light leading-5 text-neutral-500"
                        >
                          Banks integrating DFT position themselves as fintech
                          innovators, enhancing their brand as leaders in
                          technology adoption
                        </div>
                      </div>
                      <div
                        class="flex flex-col justify-center p-3.5 mt-5 bg-white rounded-xl border border-solid shadow-lg border-black border-opacity-10 gap-5"
                      >
                      <div class="flex w-10 h-10 p-x-2.5 p-y-2.5 justify-center items-center rounded-md bg-fafa" style="background-color: #DFEEFF;">
                        <div class="w-full aspect-square">
                          <Checkbox />
                        </div>
                      </div>
                        <div
                          class="mt-6 text-lg font-medium leading-6 text-zinc-800"
                        >
                        Compliance Efficiency
                        </div>
                        <div
                          class="mt-2 text-xs font-light leading-5 text-neutral-500"
                        >
                        DFT's compliance tools aid banks in meeting
                        regulations efficiently, simplifying reporting and 
                        audits with automated transaction recording.
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>