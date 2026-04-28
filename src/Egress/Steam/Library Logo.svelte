<script>
	import Logo from '$lib/images/Egress/Logo.png';
</script>

<div class="main-capsule">
	<img src={Logo} alt="Logo" width={150} />
	<div class="text">
		<div class="title">Egress</div>
		<div class="subtitle">GRAVITY &amp; ESCAPE</div>
	</div>
</div>

<style>
	.main-capsule {
		display: grid;
		grid-auto-flow: column;
        place-content: center;
		gap: 40px;
        width: 640px;
        height: 360px;
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
		font-size: 90px;
		color: var(--gold);
		letter-spacing: 0.12em;
		text-shadow:
			0 0 40px #c8a84a80,
			0 0 80px #c8a84a33;
	}

	.subtitle {
		font-family: Cinzel;
		font-size: 20px;
		letter-spacing: 0.55em;
		color: var(--gold-lt);
	}
</style>
