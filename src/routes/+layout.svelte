<script>
	import '$lib/style.css'
	import Header from '$lib/Header.svelte'
	import Footer from '$lib/Footer.svelte'
</script>

<div class="wrapper">
	<Header />
	<main>
		<slot />
	</main>
	<Footer />
</div>

<style>
	.wrapper {
		min-height: 100dvh;
		display: grid;
		grid-template-rows: auto 1fr auto;
	}
</style>
