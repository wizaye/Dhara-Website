<script>
	import FirstSvg from '$lib/img/scroll-text-color.svelte';
	import SecondSvg from '$lib/img/scroll-text-dark.svelte';
</script>

<div class="relative h-20 overflow-hidden whitespace-nowrap">
	<div class="flex animate-scroll-svg justify-evenly space-x-8">
		{#each Array(4) as _, index}
			<div class="mr-30 mx-8 inline-block">
				<FirstSvg />
			</div>
			<div class="mr-30 mx-8 inline-block">
				<SecondSvg />
			</div>
		{/each}
	</div>
</div>
