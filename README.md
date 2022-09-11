![Alt text](https://camo.githubusercontent.com/8ce23a7eb4b2fb99d1b4a5c4b7a323fb17b5f12336f6753cb7b64c162c72b3d0/68747470733a2f2f63646e2e6472696262626c652e636f6d2f75736572732f35393934372f73637265656e73686f74732f31363438373536362f6d656469612f31636464616632663138653637643962663166393462363562643262303763382e6a70673f636f6d70726573733d3126726573697a653d3736387835373626766572746963616c3d746f70)
<h1 class="ml6">
  <span class="text-wrapper">
    <span class="letters">Hi, I'm Della</span>
  </span>
</h1>

<script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/2.0.2/anime.min.js"></script>
.ml6 {
  position: relative;
  font-weight: 900;
  font-size: 3.3em;
}

.ml6 .text-wrapper {
  position: relative;
  display: inline-block;
  padding-top: 0.2em;
  padding-right: 0.05em;
  padding-bottom: 0.1em;
  overflow: hidden;
}

.ml6 .letter {
  display: inline-block;
  line-height: 1em;
}
var textWrapper = document.querySelector('.ml6 .letters');
textWrapper.innerHTML = textWrapper.textContent.replace(/\S/g, "<span class='letter'>$&</span>");

anime.timeline({loop: true})
  .add({
    targets: '.ml6 .letter',
    translateY: ["1.1em", 0],
    translateZ: 0,
    duration: 750,
    delay: (el, i) => 50 * i
  }).add({
    targets: '.ml6',
    opacity: 0,
    duration: 1000,
    easing: "easeOutExpo",
    delay: 1000
  })
I'm della from Nigeria. 
I'm pursuing a new career in tech(full stack web developement)
