<script>
 import dancingCat from '$lib/assets/images/image.gif'
 let name = 'Svelte'
 let src = '/images/image.gif'
</script>

<img src="{dancingCat}" alt="">
<h1>Hello {name.toUpperCase()}!</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

<style>
p{
    color: goldenrod;
}
</style>