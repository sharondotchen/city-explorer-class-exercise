<script>
	const properties = $props();
	const info = properties.info;
	const name = info.name;
	const sights = info.topSites;
</script>

<div class = "details">
	<h3>{name} is great</h3>
	<p>You should check out the {sights}</p>
</div>

<style>
	.details{
		background: #010101;
	}
</style>