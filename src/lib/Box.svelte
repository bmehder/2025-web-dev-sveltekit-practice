<script>
	export let src
	export let heading = ''
	export let description =
		'Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptas labore aut.'
	export let href = '/'
	export let linkText = 'Read More &raquo;'
</script>

<div class="bg-white flow">
	<img {src} alt="" />
	<h3>{heading}</h3>
	<p>{description}</p>
	<a {href}>{@html linkText}</a>
</div>

<style>
	div {
		position: relative;
		padding: 2rem;
		font-size: 1.125rem;
		border-radius: 1rem;
	}

	img {
		max-width: 3.5rem;
		position: absolute;
		top: -2rem;
	}

	a {
		display: inline-block;
		font-weight: 600;
	}
</style>
