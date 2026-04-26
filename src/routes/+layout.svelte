<script>
	import favicon from '$lib/images/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}

<style>
	:global {
		body {
			margin: 0;
			min-height: 100vh;
			--bg: #0b0e14;
			--gold: #c8a84a;
			--gold-lt: #e8cc80;
			background: var(--bg);
		}

		@font-face {
			font-family: Cinzel;
			src: url('$lib/fonts/Cinzel.ttf');
		}

		@font-face {
			font-family: CD;
			src: url('$lib/fonts/Cinzel Decorative.ttf');
		}
	}
</style>
