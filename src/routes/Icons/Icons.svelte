<script lang="ts">
    import GitHub from './githubwhite.png';
    import Spotify from './spotify.png';
    import Instagram from './instagram.png';
    import LinkedIn from './linkedin.png';
    import GoogleDocs from './googledocs.png';
</script>

<div id="contact">
    <a target="_blank" rel="noopener noreferrer" href="https://github.com/ofjuneskies"><img class="button1" src={GitHub}></a>
    <a target="_blank" rel="noopener noreferrer" href="https://open.spotify.com/user/princelyss?si=c0c9ae9786604e9f"><img class="button1" src={Spotify}></a>
    <a target="_blank" rel="noopener noreferrer" href="https://www.instagram.com/ofjuneskies/"><img class="button1" src={Instagram}></a>
    <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/jennyliu623/"><img class="button1" src={LinkedIn}></a>
    <a target="_blank" rel="noopener noreferrer" href="https://docs.google.com/document/d/1JjXS0yq7JbZqVP0voa5IYHUgO0XEjCBkp9oGhGW6W1k/edit?usp=sharing"><img class="button1" src={GoogleDocs}></a>
</div>

<style>
    #contact{
        background-color: #05080f;
        height: 120px;
        text-align: center;
    }

    .button1{
        height: 60px;
        display: flex;
        gap: 50px;
        padding-top: 20px;
        margin-left: auto;
        margin-right: auto;
        width: auto;
        display: inline-block;
        margin: 10px 15px 0px 15px;

    }

    .button1:hover{
        transform: scale(1.1);
    }
</style>