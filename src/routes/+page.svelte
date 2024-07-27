<script lang="ts">
	import DFTFeaturesOverview from './DFTFeaturesOverview.svelte';

	import MainHeaderSection from './MainHeaderSection.svelte';
	import Sec3 from '@/img/Sec3.svelte';
	import { ScrollText, Shrink, Puzzle, ClockArrowUp, SearchCheck, Info } from 'lucide-svelte';
	import Footer from '@/components/blocks/footer.svelte';
	import Scroller from '@/components/blocks/scroller.svelte';
	import Fin from '@/img/fin.svelte';
</script>

<MainHeaderSection />
<section class="container">
	<button
		class="border-dharateal mx-auto flex w-fit justify-center space-x-3 rounded-md border p-2 uppercase"
	>
		<Info class="text-dharateal" />
		<p>problems</p>
	</button>
	<h2
		class="mx-auto max-w-lg py-3 text-center text-3xl tracking-tight lg:mx-0 lg:max-w-md lg:text-left lg:text-4xl"
	>
		The Bottleneck in Traditional Supply Chain Finance
	</h2>
	<div
		class="flex flex-col rounded-2xl border-b-[20px] border-green-500 bg-white p-4 drop-shadow-md"
	>
		<div class="mb-6 mt-3 size-fit rounded-lg bg-[#EBF5EB] p-2">
			<Fin />
		</div>
		<h3 class="my-5 text-2xl">Financial Ecosystems</h3>
		<p class="text-gray-500">
			There is a growing demand for financial models including all in supply chain, enabling smaller
			vendors' access to capital for growth
		</p>
	</div>
</section>

<DFTFeaturesOverview />
<Footer />
<Scroller />
