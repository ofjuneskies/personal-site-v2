<script lang="ts">
    import WICS from "./wics.png"
    import Hack from "./hack-modified.png"
    import VH from "./vh.png"
    import UCI from "./UCI.png"
</script>

<h4>experience</h4>
<div class="container row d-flex align-items-center justify-content-center mx-auto">
    <div class="parent col-xs-12 col-md-6 col-lg-3">
        <div class = "wrapper">
            <p class = "layer2 bio_text">&emsp;<i> WICS Community Outreach Committee Member & Community Outreach Co-Chair</i>
                December 2021 - Present
            </p>
            <img class="exp_image" src={WICS}> 
        </div> 
    </div>

    <div class="parent col-xs-12 col-md-6 col-lg-3">
        <div class = "wrapper">
            <p class = "layer2 bio_text">&emsp;<i>Hack at UCI Logistics & Technology Organizer</i>
                May 2023 - Present
            </p>
            <img class="exp_image" src={Hack}> 
        </div> 
    </div>

    <div class="parent col-xs-12 col-md-6 col-lg-3">
        <div class = "wrapper">
            <p class = "layer2 bio_text" >&emsp;&emsp;<i>VenusHacks Logistics Organizer</i>
                January 2023 - June 2023
            </p>
            <img class="exp_image" src={VH}> 
        </div> 
    </div>
    
    <div class="parent col-xs-12 col-md-6 col-lg-3">
        <div class = "wrapper">
            <p class = "layer2 bio_text">&emsp;<i>ICS 31 Learning Assistant Organizer</i>
                September 2022 - December 2022
            </p>
            <img class="exp_image" src={UCI}> 
        </div> 
    </div>            
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
    }


    .exp_image{
        flex-basis: 20%;
        position: relative;
        right: 0px;
        transition: 1.5s;
        overflow: hidden;
        margin-bottom: 30px;
        overflow: hidden;
        height: 310px;
        min-width: 155px;
    }

    .container{
        display: flex;
        align-items: center;
        justify-content: center
    }
    .wrapper{
        display: grid;
        align-items: center;
        justify-content: center;
    }

    .wrapper:hover .exp_image{
        transition: 0.8s;
        opacity: 0;
    }

    .parent {
        position: relative;
        top: 0;
        left: 0;
    }

    .layer2 {
        position: absolute;
        font-family: Silkscreen;
        color: white;
        display: grid;
        vertical-align: middle;
        left: 50%;
        transform: translateX(-50%)
    }

    .bio_text{
        font-size: 14px;
        max-height: 300px;
        min-width: 200px;
    }
</style>