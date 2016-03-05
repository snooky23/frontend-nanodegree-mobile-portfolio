Read me: 

1. In order to check task 1 (get more than 90 score in the index.htm with google insights) I uploaded my soultion to github pages. (The page is registred with my google-analytics new user:)
Please use the below link in otder to check,

https://developers.google.com/speed/pagespeed/insights/?url=http%3A%2F%2Fsnooky23.github.io%2Ffrontend-nanodegree-mobile-portfolio%2F&tab=mobile

2. In task 2 (pizza), the main fixes was:

Fixed issues:
- ChangePizzaSizes method, create a variable for getElementsByClassName("randomPizzaContainer") all actions should use the same one.
- Replaced querySelector & querySelectorAll with getElementById & getElementsByClassName
- updatePositions method, Separate the for loops to two independent for loops, they need to be loosely coupled (seperate loops)
- ChangePizzaSizes method, fix multiple calls to the dom & make the method easier to calc sizes by taking out calculation that has the same resulte from a loop.
- ChangePizzaSizes & updatePositions methods, save the array length in local variable instead of calc it in every loop iteration.
- Declare the pizzasDiv variable (var pizzasDiv = document.getElementById('randomPizzas');) outside the loop, so the function only makes one DOM call
-  'DOMContentLoaded' listener, reduced background pizzas should be to at least 24 a multiple of the current cols value & Declaring the elem variable (var elem;) outside the loop
- CSS 'Mover', increase site performance with hardware accelerated CSS


in order to check that the task is working pleae use the folowing link:

http://snooky23.github.io/frontend-nanodegree-mobile-portfolio/views/pizza.html?#locations