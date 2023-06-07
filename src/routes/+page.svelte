<script>
    import Header from "../components/Header.svelte";
    import Hero from "../components/Hero.svelte";
</script>

<style>
    :global(*) {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
</style>

<!-- markup (zero or more items) goes here -->

<svelte:head>
    <title>Mi blog</title>
</svelte:head>

<Header></Header>
<Hero></Hero>