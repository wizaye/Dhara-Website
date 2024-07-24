<script lang="ts">
	import Navbar from '@/components/blocks/navbar.svelte';
	import leftGif from '$lib/img/b3151c0a6afdefc2137c73255408a557-ezgif.com-crop.gif';
	import rightGif from '$lib/img/111abeed6207fb60b16fc333a023d217-ezgif.com-crop.gif';
	import { Play } from 'lucide-svelte';
</script>

<Navbar />

<div class="container relative mx-auto mt-20 px-4 py-8">
	<h1 class="mb-4 text-center text-6xl font-bold text-gray-500">Deep Financing Tokens</h1>

	<div class="mb-4">
		<p class="text-center text-6xl text-gray-500">A Fintech Innovation</p>
	</div>

	<div class="flex justify-center">
		<div class="mr-4 w-1/2">
			<img src={leftGif} alt="GIF 1" class="w-full" />
		</div>
		<p class="max-w-2xl text-center text-lg text-gray-500">
			Transforming Supply Chain Finance with Programmable Digital Assets. Bridging the Liquidity Gap
			in Global Supply Chains.
		</p>
		<div class="ml-4 w-1/2">
			<img src={rightGif} alt="GIF 2" class="w-full" />
		</div>
	</div>

	<div class="mx-auto mt-8 flex items-center justify-center" style="top: 250px; left: 50%;">
		<button
			type="button"
			class="flex items-center space-x-2 rounded-lg bg-[#05A987] px-4 py-2 text-center text-sm font-medium text-white hover:bg-[#05A987] focus:outline-none focus:ring-4 focus:ring-[#05A987] dark:bg-[#05A987] dark:hover:bg-[#05A987] dark:focus:ring-[#05A987]"
		>
			Book a Demo
		</button>

		<button class="mx-3 flex items-center justify-center space-x-2 rounded-lg bg-white px-4 py-2">
			How it works <span class="ml-2 rounded-full bg-[#05A987] p-1"
				><Play class="fill-white" size={12} /></span
			></button
		>
	</div>
</div>
