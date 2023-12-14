<script>
    import PrimaryButton from '/src/components/PrimaryButton.svelte';
    import SecondaryButton from '/src/components/SecondaryButton.svelte';


</script>

<main>
    <section>

        <h1>Wir geben<br> Ihrem Unternehmen Stil</h1>

        <div class="buttons">
            <PrimaryButton link="/kontakt">Kontaktiere uns</PrimaryButton>
            <SecondaryButton link="/service">Service</SecondaryButton>
        </div>
    </section>
</main>


<main class="services">
    <section class="service">
        <a href="/service"><img src="images/services/design-service.svg" alt="design service"></a>
        <a href="/service"><img src="images/services/foto-service.svg" alt="foto service"></a>
        <a href="/service"><img src="images/services/video-service.svg" alt="video service"></a>
        <a href="/service"><img src="images/services/aufkleber-service.svg" alt="aufkleber service"></a>
    </section>
</main>


<style>
    .service{
        background-color: #efefef;
        display: flex;
        justify-content: space-between;
        align-items: center;
        flex-wrap: wrap;
        
    }

    .service a{
        border-radius: 1rem;
        box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
        width: 24%;
        transition: all 0.2s ease-in-out;
    }

    .service a:hover{
        background-color: #ef233c;
    }

    img{
        
        width: 100%;
        transition: all 0.1s ease-in;
    }

    img:hover{
        filter: invert(100%) sepia(58%) saturate(232%) hue-rotate(181deg) brightness(119%) contrast(87%);
        scale: 1.025;
        cursor: pointer;
    }
    h1{
        font-size: 72px;
        color: #2b2d42;
    }
</style>