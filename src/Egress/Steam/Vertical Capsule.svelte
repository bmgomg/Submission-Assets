<script>
	import Logo from '$lib/images/Egress/Logo.png';
</script>

<div class="vertical-capsule">
	<div class="title">Egress</div>
	<img src={Logo} alt="Logo" width={200} />
	<div class="subtitle">GRAVITY &amp; ESCAPE</div>
</div>

<style>
	.vertical-capsule {
		display: grid;
		place-content: center;
		place-items: center;
		gap: 40px;
		width: 374px;
		height: 448px;
		box-sizing: border-box;
		/* border: 1px dotted gray; */
	}

	.title {
		font-family: CD;
		font-weight: 700;
		font-size: 70px;
		color: var(--gold);
		letter-spacing: 0.12em;
		text-shadow:
			0 0 40px #c8a84a80,
			0 0 80px #c8a84a33;
		line-height: 1em;
	}

	.subtitle {
		font-family: Cinzel;
		font-size: 17.5px;
		letter-spacing: 0.5em;
		color: var(--gold-lt);
	}
</style>
