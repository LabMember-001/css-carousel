# CSS Carousel
Demo: https://okabe.moe/projects/css-carousel/


CSS Carousel is a simple and customizable HTML/CSS solution to a javascript-free carousel.
You can easily add additional content in the carousel such as titles, descriptions, and links to your product with full in-carousel HTML compatability.

To change the location of the selector bubbles set ```top``` class to the carousel-selector element.

To enable or disable the buttons signalling that you can click on the sides you can choose whether or not you want to generate the spans.

To change the location of the selected container for titles and descriptions, simply add the ```bottom``` class to the container and a ```<span class="selector-spacer"></span>``` element at the start/end of the selected-container if your selector bubbles are also at the same side as your titles.

When dynamically generating pages with multiple css carousels it is important to keep the input/label names and id's unique for each carousel so they do not collide and share inputs or break. It is also important that you remember to set the correct amount and carefully label the selector bubbles so their position can be calculated.
