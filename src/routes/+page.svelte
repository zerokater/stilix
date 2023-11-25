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





<style>

    main{
        display: flex;
        justify-content: center;
    }    

    section{
        margin-top: 64px;
        width: 60%;
    }

    h1{
        font-size: 64px;
        color: #2b2d42;
    }
</style>