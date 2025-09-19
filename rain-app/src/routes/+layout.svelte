<script>
	import './global.css';
</script>

<main>
	<slot />
</main>

<style>
	main {
		min-height: 100vh;
		background: #000;
		color: #fff;
		font-family: 'Courier New', monospace;
		padding: 0;
		margin: 0;
	}
</style>