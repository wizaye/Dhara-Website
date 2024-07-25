<script>
	import '../app.css';
	import Navbar from '@/components/blocks/navbar.svelte';
	import Footer from '@/components/blocks/footer.svelte';
</script>

<Navbar />
<div class="mt-20">
	<slot></slot>
</div>


