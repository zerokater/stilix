<head>
    <title>Stilix</title>
    <meta name="description" content="Kreative Branding-Agentur, die Unternehmen durch erstklassiges Branding, innovatives Design und individuelle Strategien zum Erfolg verhilft. Erfahren Sie mehr und kontaktieren Sie uns jetzt!">
	  <meta name="keywords" content="bisha, Branding-Agentur, Markenbildung, Design, Bisha Wallis, Markenstrategie, Logo-Design, Verpackungsdesign, Marketingmaterialien, Unternehmenserfolg" />
    <link rel="canonical" href="https://stilix.ch/">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
</head>

<header>
    <div class="logo">
        <a href="/">
            <img src="images/stilix-logo.svg" alt="stilix logo">
        </a>
    </div>
    <nav>
        <a href="/service">service</a>
        <a href="/kontakt">kontakt</a>
    </nav>
</header>



<slot></slot>

<style>

    :global(*){
       padding: 0;
       margin: 0;
       box-sizing: border-box;
       font-family: 'Poppins', sans-serif;
    }



    :global(html){
        font-size: 10px ;
    }

    :global(body){
        background-color: #efefef;
    }

    header{
        padding: 5rem 0rem 0rem 0rem;
        width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    nav{
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 2rem;
    }

    a{
        font-size: 22px;
        color: #2b2d42;
        text-decoration: none;
        transition: 0.2s ease-out;
    }

    a:hover{
        color: #ef233c;
    }

    img{
        width: 92px
    }

    @media only screen and (max-width: 1250px) { 
        header{
            width: 95%;
        }
     }
</style>