# Reaction Game

A "reaction testing" game created using vanilla JavaScript and CSS.

## Motivation
I am taking Rob Percival's The Complete Web Developer 2.0 course on Udemy to improve my web development skills.  Although I had already studied HTML, CSS and JavaScript in previous tutorials, I am still learning new things by taking this course.  I am creating this project without watching the instructor's solution.

## Game Instructions
Circles and squares of varying sizes and colors appear on the screen in different locations.  Click them to make them disappear, then see how long it took.

## Things I learned
- Math.random to generate random numbers to be used to style the CSS shapes
- CSS border-radius to style the shape as either a cirlce or a square
- Colors using HSV and randomly-generated numbers for the "hue" property
- Passed a random number to "set Timeout" so that shape reappeared at random times
- Used "window.innerHeight" and "window.innerWidth" as maximum random numbers to be generated for specifying a random position, subtracting the size of the element itself to keep the shape from appearing off the visible portion of the screen

## Additional features (not part of the course)
- Added a "start" button to start the game
- Total time is displayed after 10 shapes
- Best times are held in Local Storage and the player is alerted when they have achieved a new best score
