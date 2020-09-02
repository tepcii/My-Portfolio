<script>
	import Card from './components/Card.svelte';
	import Icon from './components/Icon.svelte';
	import Name from './components/Name.svelte';
	import ToggleButtons from './components/ToggleButtons.svelte';
	import AboutMe from './components/AboutMe.svelte';
	import ContactMe from './components/ContactMe.svelte';

	let currentPage = 2;
	const toggle = (index) => currentPage = index;

</script>

<main>
	<Card>
		<Icon></Icon>
		<Name></Name>
		<ToggleButtons toggle={toggle}></ToggleButtons>
		{#if currentPage == 0}
			<AboutMe></AboutMe>
		{:else if currentPage == 1}
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