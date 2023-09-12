<script>
	import logo from '$lib/assets/logo.png';
</script>

<svelte:head>
	<script async src="https://cse.google.com/cse.js?cx=4057f0107f2b1450f"></script>
</svelte:head>

<div class="container">
	<div class="img-wrapper">
		<img alt="Modesty Concept logo" src={logo} />
	</div>
	<div class="search-wrapper">
		<div class="gcse-search" />
	</div>
</div>

<style>
	.container {
		width: 100vw;
		height: 100vh;
		display: flex;
		flex-direction: column;
		background-color: #f4f3ee;
	}
	.img-wrapper {
		display: flex;
		justify-content: center;
		padding: 0, 20rem;
	}
	.img-wrapper img {
		width: 33%;
	}
	.search-wrapper {
		display: flex;
		justify-content: center;
	}
	.gcse-search {
		width: 75%;
	}
</style>
