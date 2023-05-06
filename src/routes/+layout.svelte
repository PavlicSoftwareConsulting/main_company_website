<script>
	import Header from './Header.svelte';
	import Footer from './Footer.svelte';
	import './global.css';
</script>

<div class="app">
	<Header />

	<main class='theme-darkmode'>
		<slot />
	</main>

	<Footer />
</div>

<style>
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		width: 100%;
		box-sizing: border-box;
	}
</style>
