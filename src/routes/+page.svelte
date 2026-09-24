<script>
	import dancingCat from '$lib/assets/images/image.gif';
	import Card from '$lib/Components/profile-components/Card.svelte';
	import Footer from '$lib/Components/Footer.svelte';
    import Header from '$lib/Components/Header.svelte';
	let name = 'Svelte';
</script>

<header>
	<Header/>
</header>


<main>
	<Card/>
</main>


<h1>Hello {name.toUpperCase()}!</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

<footer>
    <Footer/>
</footer>

<style>
	p {
		color: goldenrod;
	}
</style>
