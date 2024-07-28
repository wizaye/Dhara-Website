<script lang="ts">
	export let border: string = '';
	export let iconColor: string = 'EBF5EB';
</script>

<div
	class="flex h-[40vh] flex-col rounded-2xl border-b-[20px] border-{border}-500 bg-white p-4 drop-shadow-lg"
>
	<div class="mb-16 mt-3 size-fit rounded-lg bg-[#{iconColor}] p-2">
		<slot name="icon" />
	</div>
	<div class="my-5 text-xl">
		<slot name="heading" />
	</div>
	<div class="text-base text-gray-500">
		<slot name="body" />
	</div>
</div>
