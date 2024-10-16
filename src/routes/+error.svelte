<script>
	import { page } from '$app/stores'
</script>

<div class="section">
	<div class="inner">
		<h1>{$page.status}: {$page.error.message}</h1>
	</div>
</div>
