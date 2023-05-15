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
		margin-left: 3rem;
		margin-right: 3rem;
		flex: 1;
		display: flex;
		flex-grow: 1;
		flex-direction: column;
		align-items: center;
		box-sizing: border-box;
	}
</style>
