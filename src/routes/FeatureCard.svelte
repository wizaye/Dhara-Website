<script lang="ts">
	export let color = '';
</script>

<div class="flex items-center space-x-4 rounded-md bg-white p-4 drop-shadow-lg">
	<div class="rounded-lg bg-[{color}] p-4">
		<slot name="icon" />
	</div>
	<span>
		<!-- Default slot for the title -->
		<slot />
	</span>
</div>
