<script>
	import Title from '$lib/Title.svelte'

	export let data
</script>

<Title title={data.post.title}></Title>

<section>
	<div class="boxed space flow">
		<div>{data.post.body}</div>
	</div>
</section>

<style>
	div > div {
		max-width: 65ch;
	}
</style>
