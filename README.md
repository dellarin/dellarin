![Alt text](https://camo.githubusercontent.com/8ce23a7eb4b2fb99d1b4a5c4b7a323fb17b5f12336f6753cb7b64c162c72b3d0/68747470733a2f2f63646e2e6472696262626c652e636f6d2f75736572732f35393934372f73637265656e73686f74732f31363438373536362f6d656469612f31636464616632663138653637643962663166393462363562643262303763382e6a70673f636f6d70726573733d3126726573697a653d3736387835373626766572746963616c3d746f70)
// Dependencies
var TextAnimation = require("text-animation");

// Animate bottom-top
TextAnimation("Hello I'm della", function (err) {
    if (err) throw err;
    // And then, top-bottom
    TextAnimation({
        text: "...World!"
      , animation: "top-bottom"
    });
});
I'm della from Nigeria. 
I'm pursuing a new career in tech(full stack web developement)
