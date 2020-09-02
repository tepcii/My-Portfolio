<script>
	import Card from './components/Card.svelte';
	import Icon from './components/Icon.svelte';
	import Name from './components/Name.svelte';
	import AboutMe from './components/AboutMe.svelte';
	import ContactMe from './components/ContactMe.svelte';

	let currentPage = 2;

</script>

<main>
	<Card>
		<Icon></Icon>
		<Name></Name>
		{#if currentPage == 1}
			<AboutMe></AboutMe>
		{:else if currentPage == 2}
			<ContactMe></ContactMe>
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