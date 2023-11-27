<script>
    import PrimaryButton from '/src/components/PrimaryButton.svelte';
    import SecondaryButton from '/src/components/SecondaryButton.svelte';


</script>

<main>
    <section>

        <h1>Deine Vision</h1>
        <h1>
            unsere Kreation</h1>

        <div class="buttons">
            <PrimaryButton link="/kontakt">Kontaktiere uns</PrimaryButton>
            <SecondaryButton link="/service">Service</SecondaryButton>
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
        width: 1200px;
    }

    h1{
        font-size: 64px;
        width: 95%;
        color: #2b2d42;
    }


    @media only screen and (max-width: 1250px) { 
        section{
            width: 95%;
        }
     }

</style>