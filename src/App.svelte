<script>
	export let name;
</script>

<main>
	<!-- <h1>Hello {name}!</h1>
	<p>This is a starter template for a Svelte PWA, based in the <a href="https://github.com/sveltejs/template" target="_blank">Svelte template</a></p>
	<p>You will find the manifest.json file and the service-worker.js file in the public folder</p> -->
	<div id="boundary">
		<canvas id="mindfield"></canvas>
	</div>
</main>

<style>
	main {
		display: flex;
		flex-direction: column;
		align-items: center;
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

	#boundary {
		border-radius: 50%;
		background:greenyellow;
		width: 32rem;
		height: 32rem;
		padding: 9px;	
		box-shadow: 0 0 0 6px black;
	}

	#mindfield {
		background: black;
		border-radius: 50%;
		width: 32rem;
		height: 32rem;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
