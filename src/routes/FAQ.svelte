<script lang="ts">
    let faqs = [
      {
        question: "How does DFT integrate with existing financial systems?",
        answer: "DFT is designed for easy integration with traditional financial systems and digital payment platforms, ensuring a seamless transition to blockchain-based finance."
      },
      {
        question: "Is DFT suitable for businesses of all sizes?",
        answer: "Yes, DFT is designed to cater to businesses of all sizes, providing scalable solutions tailored to their specific needs."
      },
      {
        question: "What makes DFT more secure than traditional finance methods?",
        answer: "DFT leverages blockchain technology to enhance security, offering encrypted transactions and decentralized validation to prevent fraud and ensure data integrity."
      },
      {
        question: "Is DFT scalable for businesses with varying volumes of receivables?",
        answer: "Absolutely, DFT's flexible architecture allows businesses to manage varying volumes of receivables efficiently, scaling up or down based on their requirements."
      }
    ];
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
          Frequently Asked <br />Questions
        </div>
        <div
          class="mt-5 text-lg font-light leading-7 text-neutral-500 max-md:max-w-full"
        >
        Here is the list of FAQ’s about us and how we work. Got more questions? Feel free to reach us out
        </div>
      </div>
    </div>
    <div class="flex flex-col ml-5 w-[64%] max-md:ml-0 max-md:w-full">
        <div class="grow max-md:mt-10 max-md:max-w-full">
          {#each faqs as { question, answer }, index}
            <div class="mb-4">
              <details class="group border border-gray-200 rounded-md">
                <summary class="cursor-pointer py-2 px-4 rounded-md flex justify-between items-center">
                  {question}
                  <svg
                    class="w-5 h-5 ml-2 text-gray-500 group-open:rotate-180 transform transition-transform duration-200"
                    fill="none"
                    stroke="currentColor"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
                  </svg>
                </summary>
                <p class="mt-2 p-4 bg-white">{answer}</p>
              </details>
            </div>
          {/each}
        </div>
      </div>
  </div>
</div>