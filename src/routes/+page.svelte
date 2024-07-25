<script lang="ts">
	import Navbar from '@/components/blocks/navbar.svelte';
	import leftGif from '$lib/img/b3151c0a6afdefc2137c73255408a557-ezgif.com-crop.gif';
	import rightGif from '$lib/img/111abeed6207fb60b16fc333a023d217-ezgif.com-crop.gif';
	import MobileRight from '@/img/mobile-right.svelte';
	import MobileLeft from '@/img/mobile-left.svelte';
	import Cart from '@/img/cart.svelte';
	import Shop from '@/img/shop.svelte';
	import { Play } from 'lucide-svelte';
	import Sec3 from '$lib/img/Sec3.svelte';
	import { ScrollText, Shrink, Puzzle, ClockArrowUp, SearchCheck } from 'lucide-svelte';
</script>

<Navbar />

<section class="relative mx-auto mt-20 px-4 py-8">
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
		<p class="text-center text-6xl text-gray-500">A Fintech Innovation</p>
	</div>

	<div class="flex justify-center">
		<div class="mr-4 w-1/2">
			<img src={leftGif} alt="GIF 1" class="hidden w-full md:block" />
		</div>
		<div class="absolute left-0 h-fit md:hidden">
			<MobileLeft />
		</div>
		<p class="max-w-2xl text-center text-sm font-normal text-gray-500 md:text-lg">
			Transforming Supply Chain Finance with Programmable Digital Assets. Bridging the Liquidity Gap
			in Global Supply Chains.
		</p>
		<div class="absolute right-0 h-fit md:hidden">
			<MobileRight />
		</div>
		<div class="ml-4 w-1/2">
			<img src={rightGif} alt="GIF 2" class="hidden w-full md:block" />
		</div>
	</div>

	<div class="xs:mt-12 mx-6 mt-8 flex items-center justify-center lg:mx-auto lg:mt-8">
		<button
			type="button"
			class="flex items-center rounded-lg bg-[#05A987] p-2 text-center text-xs font-medium text-white hover:bg-[#05A987] focus:outline-none focus:ring-4 focus:ring-[#05A987] dark:bg-[#05A987] dark:hover:bg-[#05A987] dark:focus:ring-[#05A987] lg:p-3"
		>
			Book a Demo
		</button>

		<button class="mx-3 flex items-center justify-center space-x-2 rounded-lg bg-white px-4 py-2">
			How it works
			<span class="ml-2 rounded-full bg-[#05A987] p-1">
				<Play class="fill-white" strokeWidth={1} size={12} absoluteStrokeWidth={true} />
			</span>
		</button>
	</div>

	<div>
		<p class="mx-auto max-w-2xl text-center text-lg text-gray-500">
			Transforming Supply Chain Finance with Programmable Digital Assets. Bridging the Liquidity Gap
			in Global Supply Chains.
		</p>
	</div>
</section>

<section>
	<div class="bg-white p-8">
		<div class="flex flex-col justify-between lg:flex-row lg:px-12">
			<div class="lg:max-w-lg">
				<h1 class="mb-4 text-2xl font-semibold lg:text-4xl lg:leading-normal">
					The Programmable Supply Chain Revolution
				</h1>
				<p class="mb-6">
					At the core of Deep Financing Tokens (DFT) is the programmable supply chain, leveraging
					blockchain for unmatched flexibility and efficiency in supply chain finance.
				</p>
			</div>
			<div class="order-first mx-auto size-full justify-center lg:order-none lg:mx-0 lg:max-w-lg">
				<span class="lg:hidden">
					<Sec3 width="fit" height="fit" />
				</span>
				<span class="hidden lg:block">
					<Sec3 />
				</span>
			</div>
		</div>
		<div class="grid grid-cols-1 justify-items-stretch gap-6 py-4 md:grid-cols-2">
			<div class="flex items-center space-x-4">
				<div class="rounded-lg bg-[#DEF7EC] p-4"><ScrollText color="#28a745" /></div>
				<span>Smart Contracts Automate Token Management in Supply Chains</span>
			</div>
			<div class="flex items-center space-x-4">
				<div class="rounded-lg bg-[#FEE2E2] p-4"><ClockArrowUp color="#ff434d" /></div>
				<span>DFT: Programmable Design Enables Real-Time Supply Chain Payments</span>
			</div>
			<div class="flex items-center space-x-4">
				<div class="rounded-lg bg-[#D1FAE5] p-4"><Shrink color="#05a987" /></div>
				<span>Financial Inclusion via Programmable Supply Chains</span>
			</div>
			<div class="flex items-center space-x-4">
				<div class="rounded-lg bg-[#EDE9FE] p-4"><SearchCheck color="#855cfe" /></div>
				<span>Blockchain Ledger & DFT: Transparency for Efficient Supply Chain Finance</span>
			</div>
			<div class="flex items-center space-x-4">
				<div class="rounded-lg bg-[#FFE4E6] p-4"><Puzzle color="#f9942f" /></div>
				<span>DFT Integrates Supply Chain and Finance via APIs</span>
			</div>
		</div>
	</div>
</section>
