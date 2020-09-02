<script>
	import Card from './components/Card.svelte';
</script>

<main>
	<Card>aaa</Card>
</main>

<style>

	main {
		width: 80%;
		height: 80%;
	}

	@media screen and (max-width: 480px) {
		/* 480px以下に適用されるCSS（スマホ用） */
		width: 100%;
		height: 100%;
	}

</style>