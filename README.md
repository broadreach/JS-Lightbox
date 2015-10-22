# JS-Lightbox
Basic lightbox functionality without jQuery.

This implements a pretty basic lightbox effect for displaying larger versions of thumbnail images. Include a thumbnail by giving it a "lightbox-photo" class. Captions can be added by using a "data-caption" attribute. Because of the way I initially used this, the full-size image gets appended to a `div` with "column-wrapper" id, but this can be easily changed depending on how your page is set up.

Your HTML should look something like this:

```
<body>

  <div id="column-wrapper">
    <img class="thumb lightbox-photo" data-caption="First Photo Caption" src="">
    <img class="thumb lightbox-photo" data-caption="Second Photo Caption" src="">
 </div>
            
</body>
```
