<script>
	import NavBar from '$lib/NavBar.svelte';
</script>

<section >
	<main>
		<NavBar/>
		<slot/>
	</main>
</section>

<style>
	section {
		min-height: 100vh;

		background-color: var(--colour-0);
	}
</style>