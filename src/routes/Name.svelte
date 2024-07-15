<div class="name"></div>
<style>
@keyframes changeContent {
    0% {
      opacity: 1;
      content: "jenny liu"
    }
    17% {
      opacity: 0;
    }
    33% {
        opacity: 1;
        content: "of june skies"
    }
    50% {
        opacity: 0;
    }
    67% {
      opacity: 1;
      content: "刘书瑷";
    }
    83%{
        opacity: 0;
    }
    100% {
        opacity: 1;
        content: "jenny liu";
    }
  }

.name{
    max-height: 70px;
    min-height: 70px;
    font-family: "Lora";
    position: relative;
    text-align: center;
    color: white;
    border: none;
    font-size: 65px;
    margin-bottom: 90px;
    margin-top: 90px;
}

.name:after{
    animation-fill-mode: forwards;
    animation: changeContent 7s linear infinite forwards;
    content: 'jenny liu'
}

</style>