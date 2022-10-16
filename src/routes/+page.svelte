<script>
	import logo from '$lib/images/KAY_logo_RGB.png';
	import construstion_img from '$lib/images/under-construction-icon-14.jpg';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Kay.ua" />
</svelte:head>

<section>
	<img src={logo} class="logo" alt="logo kay.ua" />
	<img src={construstion_img} class="construction" alt="under construstion" />
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}
	.logo {
		width: 300px;
	}
	.construction {
		width: 300px;
	}
	img {
		max-width: 100%;
	}
	h1 {
		width: 100%;
	}
</style>
