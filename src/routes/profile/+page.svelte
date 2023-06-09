<script>
    import Header from "../../components/Header.svelte";
    import AboutMe from "../../components/About_me.svelte";
    import Proyectos from "../../components/Proyectos.svelte";
</script>

<style>
    :global(*) {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    :global(.centered) {
        width: 75%;
        
    }
</style>

<!-- markup (zero or more items) goes here -->

<Header></Header>
<AboutMe></AboutMe>
<Proyectos></Proyectos>