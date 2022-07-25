<svelte:head>
    <title>Home</title>
</svelte:head>

<section>
    <a class="main">
        <h1>Craft Together</h1>
        <h5>Learn more about our survival project</h5>
    </a>
    <a href="https://github.com/CraftTogether" class="plugins">
        <h1>Plugins</h1>
        <h5>Check out our custom made plugins</h5>
    </a>
    <a class="join-us">
        <h1>Join us</h1>
        <h5>Apply</h5>
    </a>
</section>

<style>
    section {
        width: 100vw;
        height: 100vh;

        display: flex;
        flex-wrap: wrap;
        align-items: center;
        justify-content: center;
        gap: 100px;
    }

    a {
        text-decoration: none;

        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;

        aspect-ratio: 16/9;
        width: 85%;
        max-width: 750px;

        background-size: cover;
        background-repeat: no-repeat;
        border-radius: 25px;
        box-shadow: 0 0 25px var(--colour-2);
    }

    .main {
        background-image: url("https://www.minecraft.net/content/dam/minecraft/home/home-hero-1200x600.jpg");
    }

    .plugins {
        background-image: url("https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmedia.istockphoto.com%2Fphotos%2Fjava-programming-picture-id1146023990%3Fk%3D6%26m%3D1146023990%26s%3D170667a%26w%3D0%26h%3DYvhXSlJM7hM-dcZeDXDrsXJaPfeob-k6hBTc2ROyLP8%3D&f=1&nofb=1");
    }

    .join-us {
        background-image: url("https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi1.wp.com%2Fwinnaijatv.com%2Fwp-content%2Fuploads%2F2020%2F11%2F%25E2%2580%2598Minecraft-moderators-can-now-perma-ban-players-who-break-community-guidelines.jpg%3Ffit%3D2000%252C1270%26ssl%3D1&f=1&nofb=1");
    }

    h1, h5 {
        color: var(--colour-0)
    }
</style>