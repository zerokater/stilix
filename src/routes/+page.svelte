<script>
    import PrimaryButton from '/src/components/PrimaryButton.svelte';
    import SecondaryButton from '/src/components/SecondaryButton.svelte';


</script>

<main>
    <section>

        <h1>Von der Gestaltung neuer<br>Marken bis hin zum kleinsten<br>Detail im Design</h1>
        <PrimaryButton link="/kontakt">Kontaktiere uns</PrimaryButton>
        <SecondaryButton link="/service">Service</SecondaryButton>
    </section>
</main>

<main class="projekte">
    <section>
        <div class="projekt">
            <img src="images/design.png" alt="">
            <h2>Design</h2>
        </div>
        <div class="projekt">
            <img src="images/kamera.png" alt="">
            <h2>Foto</h2>
        </div>
        <div class="projekt">
            <img src="images/videokamera.png" alt="">
            <h2>Video</h2>
        </div>
        <div class="projekt">
            <img src="images/sticker.png" alt="">
            <h2>Sticker</h2>
        </div>
    </section>
</main>





<style>

    main{
        margin-top: 64px;
        width: 100%;
        display: flex;
        align-items: center;
        flex-direction: column;
    }    

    section{
        margin: 12px 0px 12px 0px;
        width: 60%;
    }

    h1{
        font-size: 64px;
        color: #2b2d42;
    }


    .projekte{
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .projekte section{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .projekt{
        border-radius: 2rem;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        gap: 3rem;
        background-color: #ef233c;
        width: 350px;
        height: 350px;
    }

    .projekt img{
        width: 96px;
    }

    .projekt h2{
        font-size: 26px;
        color: #efefef;
    }



</style>