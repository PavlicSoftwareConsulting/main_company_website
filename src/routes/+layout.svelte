<script>
	import './global.css'
	import Header from './Header.svelte';
	import Footer from './Footer.svelte';
</script>


<Header />
<main>
	<slot />
</main>
<Footer />

<style>
	main {
        width: 100%;
        max-width: 1200px;
        margin: 0 auto;
		flex: 1;
		display: flex;
		flex-grow: 1;
		flex-direction: column;
		align-items: center;
		box-sizing: border-box;
	}
</style>
