<script>
	import Box from '$lib/images/Egress/Steam/Box Tilted.png';
</script>

<div class="header-capsule">
	<img src={Box} alt="Logo" width={160} />
	<div class="text">
		<div class="title">Egress</div>
		<div class="subtitle">GRAVITY &amp; ESCAPE</div>
	</div>
</div>

<style>
	.header-capsule {
		display: grid;
		grid-auto-flow: column;
        place-content: center;
		gap: 10px;
        width: 460px;
        height: 215px;
        box-sizing: border-box;
        /* border: 1px dotted gray; */
	}

	.text {
		display: grid;
		place-self: center;
		place-items: center;
	}

	.title {
		font-family: CD;
		font-weight: 700;
		font-size: 60px;
		color: var(--gold);
		letter-spacing: 0.12em;
		text-shadow:
			0 0 40px #c8a84a80,
			0 0 80px #c8a84a33;
	}

	.subtitle {
		font-family: Cinzel;
		font-size: 13px;
		letter-spacing: 0.6em;
		color: var(--gold-lt);
	}
</style>
