#countdown timer

I'm new to GitHub and learning the ropes.  I'm into HTML, javascript, jquery, angular, grpahics, animation and a whole lot of other things. 

This is just a countdown timer made with some javascript.  I created a button and an input and added them to the page via javascript. The start button triggers a function called startCountdown() that gets the input, turns it into actual minutes and sets an interval using the setInterval method and calls the tick event to allow something to countdown or up in milliseconds (1000).  These two items are put into golbal variables for use later: var remainingSeconds; var intervalHandle;

The startbutton also removes the inputs and calls a third function called tick().  The tick() function gets the displayTimer id and puts it into a variable. remainingSeconds is turned back into mintues and put into a variable called mins. A variable called sec is created by taking remainingSeconds * mins and then subtracting remainingSeconds.  I then concatenate mins and sec into a variable called coolTimer and coolTimer is added back into the page.

Finally, I use the Decrement operator (remainingSeconds--;) to get the timer to countdown.

That is basically it in a nutshell.

