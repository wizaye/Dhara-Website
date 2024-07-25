<script>
	let posts = [
		{
			id: 1,
			title: 'First Blog Post',
			content: 'This is the content of the first blog post.'
		},
		{
			id: 2,
			title: 'Second Blog Post',
			content: 'This is the content of the second blog post.'
		},
		{
			id: 3,
			title: 'Third Blog Post',
			content: 'This is the content of the third blog post.'
		}
	];
</script>

<div class="container mx-auto mt-12 p-4">
	<h1 class="mb-4 text-4xl font-bold">Our Blog</h1>
	{#each posts as post}
		<div class="mb-8 rounded-lg border p-4 shadow-md">
			<h2 class="mb-2 text-2xl font-semibold">{post.title}</h2>
			<p>{post.content}</p>
		</div>
	{/each}
</div>
