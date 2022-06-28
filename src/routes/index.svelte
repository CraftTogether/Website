<svelte:head>
	<title>Home</title>
</svelte:head>

<section>
	<div>
		<h1>Craft Together</h1>
		<h5>Survival Minecraft server</h5>
	</div>
</section>

<style>
	section {
		width: 100vw;
		height: 100vh;

		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	div {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;

		aspect-ratio: 16/9;
		width: 85%;
		max-width: 1750px;

		background-image: url("https://www.minecraft.net/content/dam/minecraft/home/home-hero-1200x600.jpg");
		background-size: cover;
		background-repeat: no-repeat;
		border-radius: 25px;
		box-shadow: 0 0 25px var(--colour-3);
	}

	h1, h5 { color: var(--colour-0) }
</style>