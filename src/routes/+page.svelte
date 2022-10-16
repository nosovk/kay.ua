<script>
	import logo from '$lib/images/KAY_logo_RGB.png';
	import construstion_img from '$lib/images/under_construction_PNG59.png';
	import favicon from '$lib/images/Favicon_kay.png';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Kay.ua" />
	<link rel="icon" type="image/x-icon" href={favicon} />
</svelte:head>

<section>
	<img src={logo} class="logo" alt="logo kay.ua" />
	<img src={construstion_img} class="construction" alt="under construstion" />
	<div class="contacts">
		<div>Please contact:</div>
		<div>Email: <a href="mailto:kaymydoors@gmail.com">kaymydoors@gmail.com</a></div>
		<div>Phone: <a href="tel:+380500508338">+ 38 050 050 8338</a></div>
	</div>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}
	.contacts {
		padding-top: 20px;
		font-size: 14px;
		text-align: center;
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
