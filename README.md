README

Part 1:

Running the Page http://heckelsa.github.io/frontend-nanodegree-mobile-portfolio/ in Google Page Speeds (https://developers.google.com/speed/pagespeed/insights/) the Score will be higher then 90.

Changes:
* Declared not rendering critical css
* Added critical css as inline (I'm not happy with this :()
* Moved Google Fonts to the end of the documet for a clea CRP
* Removed pictures from other host to own host
* Compressed images

Part 2:

Running the Page http://heckelsa.github.io/frontend-nanodegree-mobile-portfolio/views/pizza.html inside Google Chrome.

* Removed Declarations from Loops, which stayed the same inside the loop. Since they didn't change it's better to declare them once outside and not declare them new every turn of the loop.
* Extended Pizza Size Selection (+ Extra Small, + Extra Large)
* Changed "querySelectorAll" to "getElementById" or "getElementsByClassName" since these are more specific and more performant.
* Compressed background Pizza display to load only the number of pizzas needed to fill up the screen of the specific user. 



