# texte-symboles
A simplified demo of the text editor in Audiostat which allows the teacher to add symbols over the text to tag possible pronunciation errors by selecting small chunks of text.

Live DEMO: https://www.audiostat.ca/archive/symboles-exemple.html

Creating a Rich-text editor in HTML using JavaScript is a complex task because it often involves deactivating default text behaviors and there are A LOT of special cases.

The comments and variable names in the code are in French.

Basically, when you select characters and choose a type of error, a function inserts a span around the selected characters, and then computes the width, height, X and Y position to instantiate an SVG that fits perfectly on top of the characters.
