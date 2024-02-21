<script>
	import { Fullpage, FullpageSection } from 'svelte-fullpage';
	import { base } from '$app/paths';
</script>

<svelte:head>
	<title>Orvify</title>
	<meta
		name="description"
		content="Orvify - frontend consultants specialized in modern frameworks such as React, Vue and SAP UI5"
	/>
</svelte:head>

<Fullpage>
	<FullpageSection>
		<div>
			<h1>Orvify AB (559421-5252)</h1>
		</div>
	</FullpageSection>
	<FullpageSection>
		<div>
			<h2><a href="mailto:simon@orvify.se">simon@orvify.se</a></h2>
		</div></FullpageSection
	>
	<FullpageSection>
		<div>
			<img src={`${base}/orvify-logo.svg`} alt="Orvify AB logo" />
		</div></FullpageSection
	>
</Fullpage>

<style>
	:global(body) {
		height: 100vh;
		font-family: helvetica, arial, sans-serif;
	}
</style>
