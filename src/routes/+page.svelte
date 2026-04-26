<script>
	import HeaderCapsule from '../Egress/Steam/Header Capsule.svelte';
	import MainCapsule from '../Egress/Steam/Main Capsule.svelte';
	import VerticalCapsule from '../Egress/Steam/Vertical Capsule.svelte';
</script>

<div class="app">
	{#if false}
		<HeaderCapsule />
	{/if}
	{#if false}
		<MainCapsule />
	{/if}
	{#if true}
		<VerticalCapsule />
	{/if}
</div>

<style>
	.app {
		height: 100dvh;
		display: grid;
		place-content: center;
		place-items: center;
		gap: 10px;
		background:
			radial-gradient(ellipse 70% 50% at 15% 10%, #c8a84a20 0%, transparent 60%),
			radial-gradient(ellipse 60% 70% at 85% 90%, #4a9fd428 0%, transparent 60%),
			radial-gradient(ellipse 40% 40% at 50% 50%, #50d09010 0%, transparent 70%);
	}
</style>
