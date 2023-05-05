<script>
    export let theme = 'lightmode';

    function toggleTheme() {
        theme = theme === 'lightmode' ? 'darkmode' : 'lightmode';
        document.body.setAttribute('data-theme', theme);
    }
</script>

<button on:click={toggleTheme}>
    {#if theme === 'lightmode'}
        Dark mode
    {:else}
        Light mode
    {/if}
</button>

<style>
</style>