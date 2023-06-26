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
		min-height: 100vh;
		background-color: var(--color-gray-dark);
	}
</style>
