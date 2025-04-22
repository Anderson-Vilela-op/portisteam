<script>
    import App from "$lib/components/templates/App.svelte";
    import HomePage from "$lib/components/pages/HomePage.svelte";
</script>

<App>
    <HomePage />
</App>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap');

    :global(body) {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: "Inter", sans-serif;
    }
</style>
