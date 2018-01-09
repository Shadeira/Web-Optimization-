
## Website Performance Optimization - Project 

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository and inspect the code.

### Getting started

#### Part 1: Optimize PageSpeed Insights score for pizza.html

Some useful tips to help you get started:

1. Check out the repository
1. To inspect the site on your phone, you can run a local server

## Instructions 

To view the pizza website download all of the files and open views/pizza.html in your browser.
To view the pizza website download all of the files and open index.html in your browser.

## Changes made : steps of the optimizations 

index.html renders at least 90 fps

-Reduced Pizza Elements
(main.js) - 529
Reduced the amount of sliding pizza elements generated from 200 down to 31, which still sufficiently fills the screen with sliding pizzas.
 
 
-Improved Efficiency
(main.js) - 505
Moved the calculation which utilizes the scrollTop method outside of the loop.

-Reduced Browser Paint Events
(main.js) - 533,534
Removed height and width styles from the generated pizza elements.
