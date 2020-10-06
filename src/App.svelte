<script>
	export let name;
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>:o GUCCI ON MY FACE!!!!!!!!!!!!!</p>
	<img src="https://cdn.discordapp.com/emojis/763071419047215115.png?v=1" alt="he didnt have gucci on my face" />
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

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>