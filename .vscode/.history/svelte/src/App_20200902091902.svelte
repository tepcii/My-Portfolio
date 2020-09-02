<script>
	import Card from './components/Card.svelte';
</script>

<main>
	<Card>

	</Card>
</main>

<style>

	main {
		width: 80%;
		height: 80%;
		display: flex;
		justify-content: center;
        align-items: center;
	}

	@media screen and (max-width: 480px) {
		/* 480px以下に適用されるCSS（スマホ用） */
		main {
			width: 100%;
			height: 100%;
		}
	}

</style>