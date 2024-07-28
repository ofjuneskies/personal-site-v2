<div id = "spotify">
    june tunes ☆彡
    <div class="playlists">
        <div class="song">

            <iframe 
                style="border-radius:12px" 
                src="https://open.spotify.com/embed/playlist/1PMGuAOlH70DP0gDDzZlUZ?utm_source=generator" 
                width="100%" 
                height="352" 
                frameBorder="0" 
                allowfullscreen="" 
                allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" 
                loading="lazy">
            </iframe> 
        </div>
     
        <div class="song">
            <iframe 
                style="border-radius:12px" 
                src="https://open.spotify.com/embed/playlist/4j1du8VIKnH3MNWHUVYzNA?utm_source=generator" 
                width="100%" 
                height="352" 
                frameBorder="0" 
                allowfullscreen="" 
                allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" 
                loading="lazy">
            </iframe>
        </div>
        <div class="song">
            <iframe 
                style="border-radius:12px" 
                src="https://open.spotify.com/embed/playlist/0k0P5bAAhBgTvBGxqbhOLu?utm_source=generator" 
                width="100%" 
                height="352" 
                frameBorder="0" 
                allowfullscreen="" 
                allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" 
                loading="lazy">
            </iframe> 
        </div>
    </div>
</div>

<style>
    
    #spotify{
        margin: 10vw 15vw 10vw 15vw;
        padding: 50px 40px 50px 40px;
        background-color: #a5aad1;
        line-height: 1;
        border: 7px solid #8387a8;
        border-radius: 50px;
        /* vertical-align: middle; */

        /* text */
        text-align: center;
        font-size: 50px;
        letter-spacing: 2px;
        font-family: "Josefin Sans";
        color: white;
            
    }


    .playlists{
        margin-top: 40px;
        display: flex;
        gap: 20px;
        flex-wrap: wrap;
        padding: 10px;
    }

    .song {
        flex: 1 1 100%;
    }

    @media (min-width: 768px) {
        .song {
            flex: 1 1 calc(33.333% - 20px);
        }
    }
</style>