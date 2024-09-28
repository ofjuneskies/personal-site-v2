<script>
    import { SquareArrowOutUpRight } from 'lucide-svelte';
</script>

<div class="exp">
    <h4>projects & research</h4>
    <a class="title" href="https://github.com/ofjuneskies/personal-site-v2" target="_blank" rel="noopener noreferrer">personal site <SquareArrowOutUpRight size={16} /></a>
        <p class="subtitle">
            <i>this site!</i>
            <br>html/css, sveltekit, vercel
        </p>
    <br>
    <a class="title" href="https://github.com/ango10/LAHACKS24" target="_blank" rel="noopener noreferrer">recipes reimagined <SquareArrowOutUpRight size={16} /></a>
        <p class="subtitle">
            <i>my project for lahacks '24 to help with food sustainability</i>
            <br>python, javascript, html, tailwindcss, mongodb, fastapi, react.js, gemini ai
        </p>
        <a class="subtitle" href="https://youtu.be/bG4UowASTEo?si=jipYgi8OnBsT6pc9" target="_blank" rel="noopener noreferrer">video demo <SquareArrowOutUpRight size={12} /></a>
    <br>
    <a class="title" href="https://github.com/hits-sdo/hits-sdo-similaritysearch" target="_blank" rel="noopener noreferrer">hits-sdo <SquareArrowOutUpRight size={16} /></a>
        <p class="subtitle">
            <i>undergraduate research focused on machine learning that utilized data taken by nasa's solar dynamics observatory</i>
            <br>python, pytorch lightning, jupyter notebooks, scikit-learn, numpy, lightly
        </p>
        <a class="subtitle" href="https://drive.google.com/file/d/1KMLGNM__WcUGJmFKJHS9OdXqEqTi_0VY/view" target="_blank" rel="noopener noreferrer">video demo <SquareArrowOutUpRight size={12} /></a>
    <br>
    <a class="title" href="https://boundaryrss.org/" target="_blank" rel="noopener noreferrer">boundary rss <SquareArrowOutUpRight size={16} /></a>
        <p class="subtitle">
            <i>undergraduate research oriented around creating a system that detects subsurface pollutants, <br>focused on the system concerning synthetic aperture radar data collected from satellites</i>
            <br>python, tensorflow, arcgis, snap, numpy
        </p>
    <br>
    <a class="title" href="https://hack.ics.uci.edu/" target="_blank" rel="noopener noreferrer">hack site <SquareArrowOutUpRight size={16} /></a>
        <p class="subtitle">
            <i>club website for hack at uci</i>
            <br>html/css, javascript, next.js, react, vercel
        </p>
</div>

<style>
    h4{
        font-family: "Anton";
        font-size: 40px;
        color: white;
        letter-spacing: 6px;
        text-align: center;
        margin-bottom: 40px;
        font-weight: normal;
        margin-top: 100px;
    }

    .title{
        text-decoration: none;
        font-family: 'Times New Roman', Times, serif;
        color: white;
        text-align: center;
        line-height: 200%;
        font-size: 28px;
        display:block;
        font-weight: bold;
    }

    a:hover {
        text-decoration: underline;
    }

    a:visited {
        text-decoration: none;
    }

    .subtitle{
        text-decoration: none;
        font-family: 'Times New Roman', Times, serif;
        color: white;
        text-align: center;
        line-height: 200%;
        font-size: 20px;
        display:block;
    }

    .link-icon{
        height: 20px;
        width: 20px;
    }

</style>