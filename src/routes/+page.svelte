<script lang="ts">
    import Clouds from './Clouds/Clouds.svelte';
    import Name from './Name/Name.svelte';
    import About from './About/About.svelte';
    import Experience from './Experience/Experience.svelte';
    import Quote from './Quote/Quote.svelte'
    import Projects from './Projects/Projects.svelte'
    import Music from './Music/Music.svelte'
    import Icons from './Icons/Icons.svelte'
</script> 

<!-- HTML -->

<svelte:head>
    <title>Of June Skies</title>
    
    <link href='https://fonts.googleapis.com/css?family=Silkscreen' rel='stylesheet'>
    <link href='https://fonts.googleapis.com/css?family=Anton' rel='stylesheet'>
    <link href='https://fonts.googleapis.com/css?family=Josefin Sans' rel='stylesheet'>
    <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400..700;1,400..700&display=swap" rel="stylesheet">

    
</svelte:head>


<header>
    <div class = "banner">
        <Name></Name>
        <Clouds dir="up"></Clouds>
    </div>
    <Clouds dir="down"></Clouds>
</header>

<main>
    <About></About>
    <Experience></Experience>
    <Quote></Quote>
    <Projects></Projects>
    <Music></Music>

    <div class = "justClouds">
        <Clouds dir="up"></Clouds>
        <Clouds dir="down"></Clouds>
    </div>
     
</main>

<footer>
    <div class = "ground"></div>
    <Icons></Icons>
</footer>

<!-- CSS -->
<style>
    :global(*){
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    main{
        padding: 1px 0;
        background-image: linear-gradient(#bda5c5, #aa9cc0, #a99bbf, #c8acc3, #d2abc0, #b6a3c1);
    }

    .banner{
        position: relative;
        width: 100%;
        height: 100vh;
        background: url(/src/routes/Images/sky1.jpg);
        background-size: cover;
        background-position: bottom;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .ground{
        /* position: absolute; */
        width: 100%;
        height: 100vh;
        background: url(/src/routes/Images/ground.jpg);
        background-size: cover;
        background-position: bottom;
        display: flex;
        justify-content: center;
        align-items: center;

    }


    .justClouds{
        position: relative;
        width: 100%;
        height: 100vh;
        background-size: cover;
        background-position: bottom;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    footer{
        background-color: #05080f;
    }

</style>