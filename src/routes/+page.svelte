<script lang="ts">
	import DFTFeaturesOverview from './DFTFeaturesOverview.svelte';

	import MainHeaderSection from './MainHeaderSection.svelte';
	import Sec3 from '@/img/Sec3.svelte';
	import { ScrollText, Shrink, Puzzle, ClockArrowUp, SearchCheck, Info } from 'lucide-svelte';
	import Footer from '@/components/blocks/footer.svelte';
	import Scroller from '@/components/blocks/scroller.svelte';
</script>

<MainHeaderSection />

<span
	class="border-dharateal mx-auto flex w-fit justify-center space-x-3 rounded-md border p-2 uppercase"
>
	<Info class="text-dharateal" />
	<p>problems</p>
</span>

<DFTFeaturesOverview />
<Footer />
<Scroller />
