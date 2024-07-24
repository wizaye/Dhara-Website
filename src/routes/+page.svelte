<script lang="ts">
	import Navbar from '@/components/blocks/navbar.svelte';
	import Sec3 from '$lib/img/Sec3.svelte';
	import { ScrollText, Shrink, Puzzle, ClockArrowUp, SearchCheck } from 'lucide-svelte';
</script>

<Navbar />

<div class="container mx-auto mt-20 px-4 py-8">
	<h1 class="mb-4 text-center text-6xl font-bold text-gray-500">Deep Financing Tokens</h1>

	<div class="mb-4">
		<p class="text-center text-6xl text-gray-500">A Fintech Innovation</p>
	</div>

	<div>
		<p class="mx-auto max-w-2xl text-center text-lg text-gray-500">
			Transforming Supply Chain Finance with Programmable Digital Assets. Bridging the Liquidity Gap
			in Global Supply Chains.
		</p>
	</div>
</div>


<section>
	<div class="p-8 bg-white">
		<div class="flex flex-row justify-items-stretch">
			<div class="basic-1/2 ">
				<h1 class="text-3xl font-bold mb-4 ">The Programmable Supply Chain Revolution</h1>
				<p class="mb-6">
					At the core of Deep Financing Tokens (DFT) is the programmable supply chain, leveraging blockchain for unmatched flexibility and efficiency in supply chain finance.
				</p>
			</div>
			<div class="basic-1/2"><Sec3 /></div>
		</div>
		<div class="grid grid-cols-1 md:grid-cols-2 gap-6 py-4 justify-items-stretch ">
			<div class="flex items-center space-x-4">
				<div class="p-4 rounded-lg bg-[#DEF7EC]"><ScrollText color="#28a745" /></div>
				<span>Smart Contracts Automate Token Management in Supply Chains</span>
			</div>
			<div class="flex items-center space-x-4">
				<div class="p-4 rounded-lg bg-[#FEE2E2]"><ClockArrowUp color="#ff434d" /></div>
				<span>DFT: Programmable Design Enables Real-Time Supply Chain Payments</span>
			</div>
			<div class="flex items-center space-x-4">
				<div class="p-4 rounded-lg bg-[#D1FAE5]"><Shrink color="#05a987" /></div>
				<span>Financial Inclusion via Programmable Supply Chains</span>
			</div>
			<div class="flex items-center space-x-4">
				<div class="p-4 rounded-lg bg-[#EDE9FE]"><SearchCheck color="#855cfe" /></div>
				<span>Blockchain Ledger & DFT: Transparency for Efficient Supply Chain Finance</span>
			</div>
			<div class="flex items-center space-x-4">
				<div class="p-4 rounded-lg bg-[#FFE4E6]"><Puzzle color="#f9942f" /></div>
				<span>DFT Integrates Supply Chain and Finance via APIs</span>
			</div>
		</div>
</section>
