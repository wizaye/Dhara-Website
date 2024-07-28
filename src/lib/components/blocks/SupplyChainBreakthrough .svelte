<script lang="ts">
	import BottleneckMobile from '@/components/blocks/BottleneckMobile.svelte';
	import { Info } from 'lucide-svelte';
	import Fin from '@/img/fin.svelte';
	import Bar from '@/img/bar.svelte';
	import Dom from '@/img/dom.svelte';
	import Store from '@/img/store.svelte';

	const content = [
		{
			heading: 'Financial Ecosystems',
			body: "There is a growing demand for financial models including all in supply chain, enabling smaller vendors' access to capital for growth.",
			border: 'pink',
			iconColor: 'EBF5EB'
		},
		{
			heading: 'Liquidity Opportunity',
			body: 'Democratizing liquidity access empowers the supply chain, fostering stability, innovation, and a resilient market ecosystem.',
			border: 'purple',
			iconColor: 'F2EEFE'
		},
		{
			heading: 'Traditional Financing Dominance',
			body: 'Conventional financial systems favor larger, established companies, leaving smaller suppliers in the supply chain with few options and higher costs.',
			border: 'red',
			iconColor: 'DFEEFF'
		},
		{
			heading: 'Restricted Vendor Access',
			body: 'Tier 263 vendor often face hurdles securing finance, leading to cash flow constraints that hamper their operational capabilities and growth potential.',
			border: 'orange',
			iconColor: 'FAF0E6'
		}
	];
</script>

<!-- Bottleneck section -->
<section class="container">
	<button
		class="mx-auto flex w-fit justify-center space-x-3 rounded-md border border-dharateal p-2 uppercase"
	>
		<Info class="text-dharateal" />
		<p>problems</p>
	</button>
	<h2
		class="mx-auto max-w-lg py-3 text-center text-3xl tracking-tight lg:mx-0 lg:max-w-md lg:text-left lg:text-4xl"
	>
		The Bottleneck in Traditional Supply Chain Finance
	</h2>
	<div class="md:hidden">
		{#each content as { heading, body, border, iconColor }, i}
			<BottleneckMobile {border} {iconColor}>
				<svelte:fragment slot="icon">
					{#if i == 0}
						<Fin />
					{:else if i == 1}
						<Bar />
					{:else if i == 2}
						<Dom />
					{:else if i == 3}
						<Store />
					{/if}
				</svelte:fragment>
				<h3 slot="heading">{heading}</h3>
				<p slot="body">
					{body}
				</p>
			</BottleneckMobile>
		{/each}
	</div>
</section>
<!-- End of Bottleneck section -->
