<script>
    import Cabecera from "$lib/items.svelte";
    const tit_pag = "bikayaks"
</script>

<style>
    .kayax {
        width: 100%;
        max-width: 42rem;
        margin: 4rem auto 0 auto;
    }
</style>

<svelte:head>
    <title>{tit_pag}</title> 
</svelte:head>

<div class="kayax" style="width:fit-content; height:fit-content; overflow: scroll;">

<h1>{tit_pag}</h1>
<body>
<Cabecera />
</body>

</div>
   

