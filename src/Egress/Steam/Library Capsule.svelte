<script>
	import Box from '$lib/images/Egress/Steam/Box Tilted.png';
</script>

<div class="library-capsule">
	<div class="title">Egress</div>
	<img src={Box} alt="Logo" width={220} />
	<div class="subtitle">GRAVITY &amp; ESCAPE</div>
</div>

<style>
	.library-capsule {
		display: grid;
		place-content: center;
		place-items: center;
		gap: 40px;
		width: 300px;
		height: 450px;
		box-sizing: border-box;
		/* border: 1px dotted gray; */
	}

	.title {
		font-family: CD;
		font-weight: 700;
		font-size: 56px;
		color: var(--gold);
		letter-spacing: 0.12em;
		text-shadow:
			0 0 40px #c8a84a80,
			0 0 80px #c8a84a33;
		line-height: 1em;
	}

	.subtitle {
		font-family: Cinzel;
		font-size: 15px;
		letter-spacing: 0.4em;
		color: var(--gold-lt);
	}
</style>
