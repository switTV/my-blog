<script>
    
</script>

<style>
        .container_Proyectos_cards {
            display: grid; 
            grid-template-columns: 1fr 1fr 1fr; 
            grid-template-rows: 1fr;
            gap: 0px 20px;
            grid-template-areas: 
            "proyecto1 proyecto2 proyecto_3"; 
        }
        
        .Proyectos .container_Proyectos_cards p{
            font-family: "Roboto Mono", monospace;
            font-size: 14px;
        }
        
        .Proyectos .container_Proyectos_cards h3{
            font-family: "Noto Sans Mono", monospace;
            margin-bottom: 5px;
            font-size: 22px;
        }
        
        .Proyectos {
            display: flex;
            justify-content: center;
            color: #0B0A07;
            margin-top: 100px;
        }
        
        .Proyectos h2 {
            font-family: "Noto Sans Mono", monospace;
            font-size: 28px;
            margin-bottom: 20px;
            border-bottom: 2px solid #0b0a0741;
            padding-bottom: 10px;
            text-align: center;
        }
</style>

<!-- markup (zero or more items) goes here -->

<div class="Proyectos">
    <div class="container_Proyectos centered">
        <h2>Proyectos</h2>
    
        <div class="container_Proyectos_cards">
            <div class="proyecto_1 proyecto">
                <h3>Pugstagram</h3>
                <p>Pugstagram es una pagina programada en <a href="https://svelte.dev/">Svelte</a> que tomando el diseño de <a href="https://instagram.com">Instagram</a> lo reversione utilizando una API de Perros.</p>
            </div>
    
            <div class="proyecto_2 proyecto">
                <h3>Hbo Minus</h3>
                <p>Hbo minus es una pagina de informacion de peliculas con la API de <a href="https://www.themoviedb.org/?language=es">The Movie DB</a> programada con HTML, CSS, JS</p>
            </div>
            <div class="proyecto_3 proyecto">
                <h3>JCF sistemas</h3>
                <p><a href="http://jcfsistemas.com/">JCF Sistemas</a> es una Landing page para distintas paginas de JCF</p>
            </div>
        </div>
    </div>
</div>