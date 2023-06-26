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
		flex: 1;
		background-color: var(--color-gray-dark);
	}
</style>
