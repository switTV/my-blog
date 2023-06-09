<script>
    import img_about_me from "../assets/imagen_AboutMe.webp";
</script>

<!-- markup (zero or more items) goes here -->

<div class="AboutMe">
    <div class="AboutMe_container centered">
        <div class="AboutMe_img">
            <img src={img_about_me} alt="" />
        </div>
        <div class="AboutMe_text">
            <h2>Maximo Galarza!</h2>
            <p>
                La programación es una expresión de sentimientos que, de la
                forma más pura, pueden ser publicados en una red de emociones.
            </p>
        </div>
    </div>
</div>

<style>
    .AboutMe {
        display: flex;
        justify-content: center;
        margin-top: 10px;
    }

    .AboutMe_container {
        /* background-color: #9BADAF; */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .AboutMe .AboutMe_container .AboutMe_img img {
        height: 400px;
        height: 400px;
        border-radius: 5px;
        box-shadow: -4px 10px 0px 4px #48CFAD;
        -webkit-box-shadow: -4px 10px 0px 4px #48CFAD;
        -moz-box-shadow: -4px 10px 0px 4px #48CFAD;
    }

    .AboutMe .AboutMe_text {
        width: 800px;
        margin-left: 25px;
    }

    .AboutMe .AboutMe_text h2 {
        margin-bottom: 10px;
        font-family: "Noto Sans Mono", monospace;
        font-size: 36px;
    }

    .AboutMe .AboutMe_text p {
        font-family: "Roboto Mono", monospace;
        font-size: 16px;
    }
</style>
