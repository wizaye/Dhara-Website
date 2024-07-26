<script>
	import { navItems } from '@/index';
	import { ArrowUpRight} from 'lucide-svelte';
	import Twitter from '@/img/twitter.svelte';
	import { Link } from 'svelte-routing';
	import Linkedin from '@/img/linkedin.svelte';
	import Instagram from '@/img/instagram.svelte';
	const links = ['Terms of Use', 'Privacy Policy', 'Contact Us'];
  </script>
  
  <footer class="font-lexend bg-white py-10 border-t border-t-solid border-gray-200">
	<div class="container mx-auto grid grid-cols-1 gap-10 md:grid-cols-3">
	  <div class="text-center md:text-left">
		<div class="flex flex-col items-center md:items-start">
		  <p class="mb-4 text-xl">
			Transform your Supply Chain Finance with Programmable Digital Assets.
		  </p>
		  <button
			class="bg-dharateal flex w-fit items-center rounded px-4 py-2 text-white hover:bg-[#048C6F]"
		  >
			Request Demo
			<ArrowUpRight class="ml-2" />
		  </button>
		</div>
	  </div>
	  <div class="text-center">
		<h2 class="mb-4 mr-5 text-lg">DHARA</h2>
		<nav class="mx-auto flex w-fit flex-col space-y-2 text-left">
		  {#each navItems as item}
			<a
			  href={item.toLowerCase().split(' ').join('-')}
			  class="hover:text-dharateal text-gray-800">{item}</a
			>
		  {/each}
		</nav>
	  </div>
	  <div class="text-left md:text-right">
		<p class="mb-4 text-left text-xl">Stay updated with the latest updates on deep finance tokenization.</p>
		<div class="flex justify-center md:justify-end">
		  <div
			class="focus-within:ring-dharateal flex w-full max-w-md overflow-hidden rounded border border-gray-300 focus-within:ring-2"
		  >
			<input
			  type="email"
			  placeholder="Email address"
			  class="flex-1 px-2 py-4 focus:outline-none"
			/>
			<button
			  class="bg-dharateal mb-2 mr-1 mt-2 rounded px-2 py-2 text-white hover:bg-[#048C6F]"
			  >Subscribe</button
			>
		  </div>
		</div>
	  </div>
	</div>
	<div class="container mx-auto mt-10 flex flex-col items-center md:flex-row md:justify-between">
	  <div class="flex flex-col mb-4 md:mb-0 items-center md:items-start">
		<p class="text-sm font-medium text-center md:text-left">Follow us on social media:</p>
		<div class="mt-2 flex justify-center md:justify-start space-x-4">
		  <!-- Social Media Icons -->
		  <a href="#twitter" class="hover:text-dharateal text-gray-600">
			<span class="inline-flex items-center justify-center w-6 h-6">
			  <Twitter/>
			</span>
		  </a>
		  <a href="#linkedin" class="hover:text-dharateal text-gray-600">
			<span class="inline-flex items-center justify-center w-6 h-6">
			  <Linkedin />
			</span>
		  </a>
		  <a href="#insta" class="hover:text-dharateal text-gray-600">
			<span class="inline-flex items-center justify-center w-6 h-6">
			  <Instagram/>
			</span>
		  </a>
		</div>
	  </div>
	  <nav class="flex space-x-4 text-center md:text-left">
		<a href="/terms" class="hover:text-dharateal text-gray-800">Terms of Use</a>
		<a href="/privacy" class="hover:text-dharateal text-gray-800">Privacy Policy</a>
		<a href="/contact-us" class="hover:text-dharateal text-gray-800">Contact Us</a>
	  </nav>
	</div>
  </footer>
  