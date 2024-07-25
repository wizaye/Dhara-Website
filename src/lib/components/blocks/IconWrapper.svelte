<script lang="ts">
	export let mobile = true;
</script>

<div class:lg:hidden={mobile} class="h-fit w-fit rounded-sm bg-[#FF434D0D] p-1">
	<div class="size-8 h-fit w-fit rounded-sm bg-white p-1 shadow-md">
		<slot />
	</div>
</div>
