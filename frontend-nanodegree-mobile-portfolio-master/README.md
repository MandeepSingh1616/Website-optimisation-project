Welcome to Website Performance Optimization portfolio project
=============================================================

The goal was to optimize a given website so that each page reaches a page speed of at least 90 measured with Page Speed Insights.

Page Open
==========
-click <a href="https://github.com/MandeepSingh1616/Website-optimisation-project/edit/master/frontend-nanodegree-mobile-portfolio-master/">here</a>
-open and unzip the file frontend-nanodegree-mobile-portfolio-master
-then lauch index.html


###Original Page Speed (of 100)

(the numbers can vary slightly dependent on the network connection)

Desktop

* index.html     =       98




Optimizations made in main.js for pizza.html
=============================================
- replaced querySelectorAll with getElementsByClassName for better performance
- make phase variable array and push  "document.body.scrollTop / 1250" in the for loop
- reduced the amount of animated pizzas from 200 to 30
- moved  calculation of "dx" and "newwidth" outside the for loop in function "changePizzaSizes" and assigned all the elements from "document.getElementsByClassName("randomPizzaContainer")"" to a variable "pizzaContainers"
- replaced "querySelector(..)" with "getElementById(..)"
 

More information for website optimisation
=========================================

## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository, inspect the code,



### Getting started

#### Tools used:

* Grunt JS
* CSS Minifier
* JS Compress
* Kraken.io

####Part 1: Optimize PageSpeed Insights score for index.html

Some useful tips to help you get started:

* Optimized Images
* Minified JavaScript
* Minified CSS
* Inline CSS styling

####Part 2: Optimize Frames per Second in pizza.html

To optimize views/pizza.html, you will need to modify views/js/main.js until your frames per second rate is 60 fps or higher. You will find instructive comments in main.js.


####Note:
I believe that my README meets all of the requirements. If I am missing something, please provide specifics about what else should be included. Thank you


