<script>
</script>
<svelte:head>
	<link href='https://fonts.googleapis.com/css?family=Press Start 2P' rel='stylesheet'>
</svelte:head>

<div class="hero" style="font-size: 2rem;">
	<div class="typo">
		<img src="/assets/hero_typo.png" height="100%" alt="MERAZ"/>
	</div>
</div>

<style lang="scss">
	.hero {
		position: relative;
		width: 100%;
		height: 100vh;
		background-image: url("/assets/hero_bg.png");
		background-size: cover;
		background-position: center;
		position: relative;
		text-align: center;
		scroll-snap-align: start;
	}
	.typo{
		position: absolute;
		height: 60vh;
		width: 95vw;
		top:50%;
		left: 50%;
		transform: translate(-50%, -50%);
		img{
			height: 100%;
			width: 100%;
			object-fit: contain;
		}
	}
</style>
