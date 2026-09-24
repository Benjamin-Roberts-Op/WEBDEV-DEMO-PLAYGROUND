<script>
 import dancingCat from '$lib/assets/images/image.gif'
 let name = 'Svelte'
 let src = '/images/image.gif'
</script>

<header>
<h1>We Learn Svelte</h1>
<nav><ul>
    <li><a href="/">Home</a></li>
    <li><a href="/">About</a></li>
    <li><a href="/">Contact</a></li>
</ul></nav>
</header>

<main>
<article>
    <figure></figure>
    <section>
        <h2>Boring Card</h2>
        <ul>
            <li>one</li>
            <li>two</li>
            <li>three</li>
        </ul>
    </section>
</article>
</main>

<footer>

</footer>

    <img src="{dancingCat}" alt="">
<h1>Hello {name.toUpperCase()}!</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

<style>
p{
    color: goldenrod;
}
</style>