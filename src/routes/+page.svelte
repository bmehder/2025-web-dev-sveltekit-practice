<script>
	import Hero from '$lib/Hero.svelte'
	import HeadingBox from '$lib/Boxes/HeadingBox.svelte'
	import Box from '$lib/Boxes/Box.svelte'
</script>

<Hero />

<section class="bg-gradient-gray">
	<div class="inner auto-fit">
		<HeadingBox heading="Check out our most popular categories!" />
		<Box heading="Animation" icon="/icons/icon-animation.svg" />
		<Box heading="Business" icon="/icons/icon-business.svg" />
		<Box heading="Design" icon="/icons/icon-design.svg" />
		<Box heading="Photography" icon="/icons/icon-photography.svg" />
		<Box heading="Programming" icon="/icons/icon-programming.svg" />
	</div>
</section>

<style>
	.inner {
		padding-block: 8rem;
	}
</style>
