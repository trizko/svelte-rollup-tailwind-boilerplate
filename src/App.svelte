<script>
    export let name
</script>

<main>
    <h1>Hello {name}!</h1>
    <p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style global type="text/postcss">
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

    main {
        text-align: center;
        padding: 1em;
        max-width: 240px;
        margin: 0 auto;
        @media (min-width: 640px) {
            max-width: none;
        }
    }
    h1 {
        color: #ff3e00;
        text-transform: uppercase;
        font-size: 4em;
        font-weight: 100;
    }
</style>
