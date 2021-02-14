<script>
	export let name;
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>This is a starter template for a Svelte PWA, based in the <a href="https://github.com/sveltejs/template" target="_blank">Svelte template</a></p>
	<p>You will find the manifest.json file and the service-worker.js file in the public folder</p>
	<canvas id="gameCanvas" width="800" height="1200"></canvas>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	#gameCanvas {
		background: black;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
