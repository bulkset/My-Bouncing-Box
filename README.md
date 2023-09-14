# Welcome to My Bouncing Box
***

## Task
So, the task had to be done so that we had a black square and it changed its location, and our browser had to have walls, as soon as the box collided, it had to change direction.
## Description
To begin with, I simply got the box itself through the getElementById function, then I created an x and y variable to put the actual location of the cube there. And then I needed to write the speed (more precisely, how much the cell will change when calling the function) of the xSpeed and ySpeed block. Next, I created a function called “moveBox”, there I first threw in the real data for the location of the box, and then took the data for the length and width of the browser window windowWidth and windowHeight. After I needed the box data, more precisely the length and width of the box, I also created variables and I put the data from the box boxWidth and boxHeight there. Next, I created a condition where the sum of the length of the location of the box and the length of the box itself will be checked to determine whether it is greater than the length of the browser window itself or whether the length of the box is less than zero, if so, then it changes direction, and also by the width (x) after which I simply changed Js code for the location of the box. And in the end it remains to use the function, for this I used the setInterval function and made sure that every 30 milliseconds the function was used and the box changed its location

## Installation
To run, just open the file in any browser

## Usage
The box moves and when it hits the wall it changes direction

```
./project index.html README.md
```

### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>
