<script lang="ts">
    import Me from './tower.jpg';
    import Stars from './Stars/Stars.svelte';
</script>


<div class = "center">
    <div class = "about">
        <Stars></Stars>
        <div class="parent">
            <div class="wrapper">
                <p class = "fun_fact">
                    Fun fact! My brand, OfJuneSkies, is my username on most platforms. It
                    was inspired by the name of an album, <i>Of June,</i> by my childhood artist
                    Owl City. I added "Skies" because I love the sky, the stars, and everything
                    beyond our atmosphere.
                </p>
                <img class="me_image" src={Me}>
            </div>
        </div>
        <h4 class="about_text">&emsp;about</h4>
        <br><br>
        <p class = "paragraph">
            Hello, my name is Jenny Liu. I’m currently a senior at University of California, Irvine 
            for a Bachelor’s degree in Computer Science and Engineering, where I gained a strong 
            foundation in both software and hardware development, developing proficiency in multiple 
            languages, including Python, C++, and Java. Being enrolled in this unique, interdisciplinary 
            course of study, I was given the chance to take a wide range of classes, from data structures 
            and machine learning, to circuits and machine code. I also sought further hands-on experience 
            in research, clubs and hackathons. I have a passion for astronomy, 
            and I hope to utilize my skillset to contribute 
            to advancements in space exploration and technology. Beyond academics, I enjoy playing video 
            games and volleyball, listening to music, and going on adventures with friends! 
        </p>
    </div>
</div>

<style>
    .center{
        max-width: max-content;
        margin: 0 auto 80px auto;
    }
    .about{
        margin: 1000px 20vw 0px 20vw;
        background: radial-gradient(circle at bottom, #311369 0, black 100%);
        padding: 4vw 4vw 4vw 2.3vw;
        line-height: 1;
        border: 7px solid #1b0a38;
        border-radius: 50px;
        overflow: hidden;
    }

    .about_text{
        font-family: "Anton";
        font-size: 3vw;
        color: white;
        letter-spacing: 6px;
        float: right;
    }

    .paragraph{
        font-family: "Josefin Sans", sans-serif;
        color: white;
        font-size: 1.5vw;
        line-height: 1.6;
        margin-left: 30px;
    }

    .me_image{
        border-radius: 20px;
        box-shadow: 8px 10px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        transition: 1.5s;
        width: 20vw;
        flex-basis: 20%;
        position: relative;
        right: 0px;
        overflow: hidden;
    }

    .parent {
        position: relative;
        top: 0;
        left: 0;
        display: flex;
        align-items: center;
        justify-content: center
    }

    .fun_fact{
        position: absolute;
        font-family: Silkscreen;
        color: white;
        display: grid;
        vertical-align: middle;
        left: 50%;
        transform: translateX(-50%);
        line-height: 1.3vw;
        font-size: 1vw;
        max-width: 20vw;
    }

    .wrapper{
        display: grid;
        align-items: center;
        justify-content: center;
    }

    .wrapper:hover .me_image {
        transition: 1.5s;
        right: 25vw; 
    }


</style>