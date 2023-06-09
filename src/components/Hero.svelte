<script>
    import Cover_img from "../assets/Cover.webp"
</script>

<style>
    .Hero {
        height: 87vh;
        background-size: 101%;
        background-position: center;
    }

    .Hero .Hero-container .Hero-text {
        font-family: "Noto Sans Mono", monospace;
        color: #F3EFF5;
        text-align: center;
    }

    .Hero .Hero-container .Hero-button a{
        background-color: #F3EFF5;
        border: #48CFAD 3px solid;
        color: #0B0A07;
        text-decoration: none;
        margin-top: 20px;

        font-family: monospace;
        font-size: 15px;

        display: flex;
        height: 40px;
        width: 150px;

        justify-content: center;
        align-items: center;

        border-radius: 2.5px;
    }
    .Hero .Hero-container .Hero-button{
        margin-top: 20px;
    }

    .Hero .Hero-container {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        height: 100%;
    }
</style>

<!-- markup (zero or more items) goes here -->

<div class="Hero" style="background-image: url({Cover_img})">
    <div class="Hero-container">
        <div class="Hero-text">
            <h1>Conoce las novedades <br> y noticias del mundo <i>tech</i></h1>
        </div>
        <div class="Hero-button">
            <a href="/blogs">Ver los blogs</a>
        </div>
    </div>
</div>