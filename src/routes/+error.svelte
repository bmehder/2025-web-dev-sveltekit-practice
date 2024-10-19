<script>
	import { page } from '$app/stores'
	import Title from '$lib/Title.svelte'
</script>

<Title title="{$page.status} {$page.error.message}" />

<div class="section">
	<div class="inner">
		<h2>Oops, something went wrong...</h2>
	</div>
</div>
