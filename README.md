## Website Performance Optimization - Project
Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the Critical Rendering Path course.

To get started, check out the repository and inspect the code.

Getting started
Part 1: Optimize PageSpeed Insights score for pizza.html
Some useful tips to help you get started:

Check out the repository
To inspect the site on your phone, you can run a local server
Instructions
To view the pizza website download all of the files and open views/pizza.html in your browser. To view the pizza website download all of the files and open index.html in your browser.

# Changes made :

- index.html 
1. renders at least 90 fps

- pizza.html
optimization of pizzeria.jpg image

- main.js : 

1. replaced document.querySelectorAll() with document.getElementsByClassName()

2. removed dx variables, replacement (newWidth)

3. reduced the number of pizzas needed in the background from 200 down to a dynamically-selected number based on window.innerHeight

4. refactored changePizzaSizes(size) get rid of unecessary functions and calls 

5. optimized the changePizzaSizes(size) function to reduce the number of calculations and functions being made within the iteration loop

6. restored style properties to both elem.style.height and elem.style.witdth




