# JS30Day2_JS_and_CSS_Clock

I started the Day 2 one thinking - "oh this looks suuper simple I'll be done with it quick!" I was right...until the glitch at the end of this project. So in this one we had to use some CSS and JavaScript in order to code a simple clock that shows the current time. I was very happy to discover the date object while working on this project, I'll be using it for another personal project of mine! 

Like I mentioned the start of it was pretty easy in getting the main functions of the clock to work, but at the end of a full cycle, the hands when going on to show us a new second, minute, or hour glitched and did a full rotation before starting again. We were left with some suggestions on how to fix it. I immedietly went for using an if statement to turn off the style temporarily. This worked very well for the second hand and while I could have simply copy and pasted my style change for each hand I wanted to do this in a shorter line. After some google searching I found a fellow JS30 challenger who went the same route that I did and learned how he solved it. 

We can set a variable of "allhands" and select the class that includes all of the hands. At first I used querySelector as I did for previous variables and cocded out the logic. Unfortunately I ran into a problem when I used the .forEach() function to grab all of the styles. After almost slamming my head against the table I disvovreed querySelectorAll which immedietly fixed my issue and I was able to fix the glitch for every hand in one function! 

I also learned a little more about arrow functions here! I very much appreciate how much cleaner ES6 makes the code we write overall!

To check out the deployed project you can click the link below:

https://rahat-ch.github.io/JS30Day2_JS_and_CSS_Clock/
