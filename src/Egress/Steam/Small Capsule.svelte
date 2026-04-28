<script>
	import Logo from '$lib/images/Egress/Logo.png';
</script>

<div class="small-capsule">
	<div class="row1">
		<img src={Logo} alt="Logo" width={36} />
		<div class="title">Egress</div>
	</div>
	<div class="subtitle">GRAVITY &amp; ESCAPE</div>
</div>

<style>
	.small-capsule {
		display: grid;
		place-content: center;
		place-items: center;
		/* gap: 10px; */
		width: 231px;
		height: 87px;
		box-sizing: border-box;
		/* border: 1px dotted gray; */
	}

	.row1 {
		display: grid;
		grid-auto-flow: column;
		gap: 12px;
	}

	img {
		grid-area: 1/1;
	}

	.title {
		grid-area: 1/2;
		font-family: CD;
		font-weight: 700;
		font-size: 36px;
		color: var(--gold);
		letter-spacing: 0.12em;
		line-height: 1.25em;
		text-shadow:
			0 0 40px #c8a84a80,
			0 0 80px #c8a84a33;
	}

	.subtitle {
		grid-area: 2/1/2 / span 2;
		font-family: Cinzel;
		font-size: 11.5px;
		letter-spacing: 0.5em;
		color: var(--gold-lt);
	}
</style>
