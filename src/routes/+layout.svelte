<script>
	import "../app.pcss";

    import NavBar from '$lib/components/NavBar/NavBar.svelte';
    import FootBar from '$lib/components/FootBar/FootBar.svelte';
	// import Analytics from '$lib/GAnalytics.svelte'
</script>

<svelte:head>
	<meta name="twitter:card" content="summary_large_image">
	<meta name="twitter:site" content="@pls_lean">
	<meta name="twitter:creator" content="@pls_lean">
	<meta name="twitter:title" content="LEAN Token">
	<meta name="twitter:description" content="Making memes and bringing users to PulseChain.">
	<meta name="twitter:image" content="https://bigjax.s3.eu-west-2.amazonaws.com/twitter-image-2.jpg">
	<meta property="og:title" content="LEAN Token">
	<meta property="og:type" content="website">
	<meta property="og:url" content="https://leantoken.org/">
	<meta property="og:image" content="https://bigjax.s3.eu-west-2.amazonaws.com/twitter-image-2.jpg">
	<meta property="og:description" content="Making memes and bringing users to PulseChain.">
</svelte:head>
<!-- <Analytics /> -->




<NavBar></NavBar>

<slot></slot>

<FootBar></FootBar>