<script>
	import { Fullpage, FullpageSection } from 'svelte-fullpage';
	import { base } from '$app/paths';
</script>

<Fullpage>
	<FullpageSection>
		<div>
			<h1>
				Orvify AB <a href="https://www.bolagsfakta.se/5594215252-Orvify_AB">(559421-5252)</a>
			</h1>
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
