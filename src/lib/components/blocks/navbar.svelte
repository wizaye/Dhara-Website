<script lang="ts">
	import { Download, Menu } from 'lucide-svelte';
	import Dhara from '$lib/img/Dhara.svelte';
	let navItems: string[] = ['About Us', 'Services', 'Contact Us', 'Blog'];
	let navOpen = false;
</script>

<nav
	class="fixed start-0 top-0 z-20 w-full border-b border-gray-200 bg-white dark:border-gray-600 dark:bg-gray-900"
>
	<div class="mx-auto flex max-w-screen-xl flex-wrap items-center justify-between p-4">
		<a href="/" class="flex items-center space-x-3 rtl:space-x-reverse">
			<span class="size-6">
				<Dhara />
			</span>
			<span
				class="self-center whitespace-nowrap text-2xl font-semibold text-[#05A987] dark:text-[#05A987]"
				>Dhara</span
			>
		</a>
		<div class="flex space-x-3 md:order-2 md:space-x-0 rtl:space-x-reverse">
			<button
				type="button"
				class="flex items-center space-x-2 rounded-lg bg-[#05A987] px-4 py-2 text-center text-sm font-medium text-white hover:bg-[#05A987] focus:outline-none focus:ring-4 focus:ring-[#05A987] dark:bg-[#05A987] dark:hover:bg-[#05A987] dark:focus:ring-[#05A987]"
				>Get the App <span class="pl-2"><Download size={18} /></span></button
			>
			<button
				data-collapse-toggle="navbar-sticky"
				type="button"
				class="inline-flex h-10 w-10 items-center justify-center rounded-lg p-2 text-sm text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600 md:hidden"
				aria-controls="navbar-sticky"
				aria-expanded="false"
				on:click={() => (navOpen = !navOpen)}
			>
				<Menu />
				<span class="sr-only">Open main menu</span>
			</button>
		</div>
		<div
			class:hidden={!navOpen}
			class=" w-full items-center justify-between md:order-1 md:flex md:w-auto"
			id="navbar-sticky"
		>
			<ul
				class="mt-4 flex flex-col rounded-lg border border-gray-100 bg-gray-50 p-4 font-medium dark:border-gray-700 dark:bg-gray-800 md:mt-0 md:flex-row md:space-x-8 md:border-0 md:bg-white md:p-0 md:dark:bg-gray-900 rtl:space-x-reverse"
			>
				<!-- <li>
					<a
						href="#"
						class="block rounded bg-[#05A987] px-3 py-2 text-white md:bg-transparent md:p-0 md:text-[#05A987] md:dark:text-[#05A987]"
						aria-current="page">Home</a
					>
				</li> -->
				{#each navItems as item}
					<li>
						<a
							href="#"
							class="block rounded px-3 py-2 text-gray-900 hover:bg-gray-100 dark:border-gray-700 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:p-0 md:hover:bg-transparent md:hover:text-[#05A987] md:dark:hover:bg-transparent md:dark:hover:text-[#05A987]"
							>{item}</a
						>
					</li>
				{/each}
			</ul>
		</div>
	</div>
</nav>
