# page-slider-js
A page slider in vanilla JS. Made famous by Apple.com a good while ago. I made this because I couldn't find a decent one in pure vanilla javascript. Oh, it's also responsive.

The script will add the ID selector of each slide to the URL when you scroll to it. When the page loads and a valid hash is in the URL, the script will scroll to that slide.

Update July 21, 2019:
Exposed to the function to move to a spesific slide so that you can create custom links.

## Initiate
Point the function to the element which contains the slides:
```html
<script>
  var mySlider = slider('.slides');
</script>
```

To create custom links, do something along the lines of:
```html
<a href="javascript:mySlider.gotoSlide('#target');">Click me please</a>
```

## Preview
* [View the page slider demo](https://kevinoes.github.io/page-slider-js/slider.html)

## Compability
Tested working in all modern desktop, tablet and mobile browsers, even including IE10 and up.
