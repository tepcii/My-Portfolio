<script>
	import Card from './components/Card.svelte';
	import Icon from './components/Icon.svelte';
	import Name from './components/Name.svelte';
	import Profile from './components/Profile.svelte';

	let currentPage = 1;

</script>

<main>
	<Card>
		<Icon></Icon>
		<Name></Name>
		{#if currentPage == 1}
			<Profile></Profile>
		{:else if currentPage == 2}

		{/if}
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