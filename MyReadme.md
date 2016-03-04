Read me: 

1. In order to check task 1 (get more than 90 score in the index.htm with google insights) I uploaded my soultion to github pages.
Please use the below link in otder to check,

https://developers.google.com/speed/pagespeed/insights/?url=http%3A%2F%2Fsnooky23.github.io%2Ffrontend-nanodegree-mobile-portfolio%2F&tab=mobile

2. In task 2 (pizza), the main fixes was:

Fixed issues:
- ChangePizzaSizes method, create a variable for getElementsByClassName("randomPizzaContainer") all actions should use the same one.
- Replaced querySelector & querySelectorAll with getElementById & getElementsByClassName
- updatePositions method, Separate the for loops to two independent for loops, they need to be loosely coupled (seperate loops)
- changePizzaSizes method, fix multiple calls to the dom & make the method easier to calc sizes by taking out calculation that has the same resulte from a loop.

in order to check that the task is working pleae use the folowing link:

http://snooky23.github.io/frontend-nanodegree-mobile-portfolio/views/pizza.html?#locations