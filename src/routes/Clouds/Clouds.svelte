<script lang="ts">
    import cloud1 from './cloud1.png';
    import cloud2 from './cloud2.png';
    import cloud3 from './cloud3.png';
    import cloud4 from './cloud4.png';
    import cloud5 from './cloud5.png';

    export let dir: "up" | "down";
</script> 

<div class = "clouds" class:flip={dir === "down"}>
    <img src = {cloud1} style="--i:1;">
    <img src = {cloud2} style="--i:2;">
    <img src = {cloud3} style="--i:3;">
    <img src = {cloud4} style="--i:4;">
    <img src = {cloud5} style="--i:5;">
    <img src = {cloud1} style="--i:10;">
    <img src = {cloud2} style="--i:9;">
    <img src = {cloud3} style="--i:8;">
    <img src = {cloud4} style="--i:7;">
    <img src = {cloud5} style="--i:6;">
</div>

<style>
    .clouds{
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        overflow: hidden;
        pointer-events: none;
        margin-top: 90px;
    }

    .clouds img{
        position: absolute;
        bottom: 0;
        max-width: 100%;
        animation: animate calc(3s * var(--i)) linear infinite;
    }

    .clouds.flip{
        transform: scaleY(-1);
        transform-origin: bottom center; 
    }

    @keyframes animate{
    0%{
        opacity: 0;
        transform: scale(1);
    }
    25%,75%{
        opacity: 1;
    }
    100%{
        opacity: 0;
        transform: scale(3);
    }
}
</style>