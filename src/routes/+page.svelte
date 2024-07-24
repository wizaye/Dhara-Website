<script lang="ts">
	import Navbar from '@/components/blocks/navbar.svelte';
</script>

<Navbar />

<section class="container relative mx-auto mt-20 px-4 py-8">
	<div class="flex justify-between lg:hidden">
		<div class="h-fit w-fit rounded-sm bg-[#FF434D0D] p-1">
			<div class="size-8 h-fit w-fit rounded-sm bg-white p-1 shadow-md">
				<Cart />
			</div>
		</div>

		<h1
			class="mb-4 mt-5 text-center text-2xl font-bold text-black md:text-3xl lg:text-6xl lg:text-gray-500"
		>
			Deep Financing Tokens
		</h1>

		<div class="h-fit w-fit rounded-sm bg-[#FF434D0D] p-1">
			<div class="size-8 h-fit w-fit rounded-sm bg-white p-1 shadow-md">
				<Shop />
			</div>
		</div>
	</div>

	<div class="mb-4">
		<p class="text-center text-2xl text-[#05A987] md:text-3xl lg:text-6xl lg:text-gray-500">
			A Fintech Innovation
		</p>
	</div>

	<div class="flex justify-center">
		<div class="mr-4 w-1/2">
			<img src={leftGif} alt="GIF 1" class="hidden w-full md:block" />
		</div>
		<p class="max-w-2xl text-center text-sm font-normal text-gray-500 md:text-lg">
			Transforming Supply Chain Finance with Programmable Digital Assets. Bridging the Liquidity Gap
			in Global Supply Chains.
		</p>
		<div class="ml-4 w-1/2">
			<img src={rightGif} alt="GIF 2" class="hidden w-full md:block" />
		</div>
	</div>
</div>
