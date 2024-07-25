<script lang="ts">
	import Dft from '@/img/DFT.svelte';
	import FeatureCard from './FeatureCard.svelte';

	import Sec3 from '@/img/Sec3.svelte';
	import { ScrollText, Shrink, Puzzle, ClockArrowUp, SearchCheck } from 'lucide-svelte';
</script>

<section>
	<div class="bg-white p-8">
		<div class="flex flex-col items-center justify-between lg:flex-row lg:px-12">
			<div class="lg:max-w-lg">
				<h1 class="mb-4 text-2xl font-semibold text-gray-700 lg:text-4xl lg:leading-normal">
					The Programmable Supply Chain Revolution
				</h1>
				<p class="mb-6 font-medium text-gray-500">
					At the core of Deep Financing Tokens (DFT) is the programmable supply chain, leveraging
					blockchain for unmatched flexibility and efficiency in supply chain finance.
				</p>
			</div>
			<div
				class="order-first mx-auto size-full items-center justify-center lg:order-none lg:mx-0 lg:inline-flex lg:max-w-lg"
			>
				<Sec3 width="fit" />
			</div>
		</div>
		<div class="grid grid-cols-1 justify-items-stretch gap-6 py-4 md:grid-cols-2">
			<FeatureCard color="#DEF7EC">
				<svelte:fragment slot="icon">
					<ScrollText color="#28a745" />
				</svelte:fragment>
				Smart Contracts Automate Token Management in Supply Chains
			</FeatureCard>

			<FeatureCard color="#FEE2E2">
				<svelte:fragment slot="icon">
					<ClockArrowUp color="#ff434d" />
				</svelte:fragment>
				DFT: Programmable Design Enables Real-Time Supply Chain Payments
			</FeatureCard>

			<FeatureCard color="#D1FAE5">
				<svelte:fragment slot="icon">
					<Shrink color="#05a987" />
				</svelte:fragment>
				Financial Inclusion via Programmable Supply Chains
			</FeatureCard>

			<FeatureCard color="#EDE9FE">
				<svelte:fragment slot="icon">
					<SearchCheck color="#855cfe" />
				</svelte:fragment>
				Blockchain Ledger & DFT: Transparency for Efficient Supply Chain Finance
			</FeatureCard>

			<FeatureCard color="#FFE4E6">
				<svelte:fragment slot="icon">
					<div class="size-7">
						<Dft />
					</div>
				</svelte:fragment>
				DFT Integrates Supply Chain and Finance via APIs
			</FeatureCard>
		</div>
	</div>
</section>
