# Optimizing idex.html for 90+ google pageinsights score

## Steps taken to optimize

1) Removed external css and included it in html using style tags with reduction in white space.
2) Added media query to print.css
3) Removed google fonts script which was unnecessary in this page.
4) Minified print.css and perfmatters.js using online minifier (http://www.minifier.org/).
5) Made google analytics script as async.
6) Resize 2mb+ pizzeria to a thumbnail level using a image editor and logo as suggested by google pageinsights
7) Moved the function in script tag to bottom of the page.
8) Minified the entire html using online minifier (https://kangax.github.io/html-minifier/)

## Steps to test
 Extract the folder and open **index.html** to view the optimized page.

# Optimizing pizza.html for 60 fps

## Steps taken to optimize

1) Removed ingredientsItemizer and gave li tags directly.
2) Query selecters were replaced by a more optimized getElementById and getElementsByClassname selectors.
3) Took document.body outside the for-loop of changePizzaSizes().
4) Removed determineDx function and modified rest of changePizzaSizes().
5) Took document.body and items.length outside the for-loop of updatePositions().
6) Set such that pizzas displayed depends on inner window dimensions.
7) Optimized pizzaria.jpg to reduce image loading time.
8) Took out variable creation from inside the for loops.

## Steps to test
 Open **pizza.html** from views folder after extraction.