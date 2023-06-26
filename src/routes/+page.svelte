<script>
	import PremiList from "../components/PremiList.svelte";

</script>
<svelte:head>
    <title>Home | VVF Vignola Falesina</title>
</svelte:head>

<div class="bg-white rounded-2xl p-2 shadow-xl">
    <h1 class="text-3xl">Sagra Vignola-Falesina 2023</h1>

    <h2>Lotteria</h2>
    <p>Estrazione il giorno 27 Agosto 2023 alle ore 18.00</p>

    <h3>Premi</h3>
    <PremiList />
</div>
<h1 class="text-4xl text-center py-6">Sito in costruzione...</h1>

<!-- <h2>Menù</h2>
<p>Il menù sarà disponibile a breve</p>

<h2>Programma</h2>
<p>Il programma sarà disponibile a breve</p>

<h2>Contatti</h2>
<p>Per informazioni contattare:</p>
<ul>
    <li>Paolo: 333 1234567</li>
    <li>Luca: 333 1234567</li>
</ul> -->

<!-- <h2>Informazioni</h2> -->



<style lang="postcss">
    :global(html) {
        background-color: theme(colors.gray.100);
    }

    h2 {
        font-size: theme(fontSize.2xl);
        font-weight: theme(fontWeight.bold);
        padding-top: theme(spacing.2);
    }

    h3 {
        font-size: theme(fontSize.xl);
        font-weight: theme(fontWeight.bold);
        padding-top: theme(spacing.1);
    }
</style>
