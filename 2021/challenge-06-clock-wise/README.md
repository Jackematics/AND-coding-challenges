# Clock-Wise

The finished solution of the clock-wise coding challenge with all stretch goals done (I have a suite of tests, but it only tests the functionality relevant to the coding challenge,
I'll let you decide whether I should get a point for it). For my own amusement, I decided to overcomplicate the task for myself by making an interactive digital clock using
canvas. I drew a mock bedroom in MS Paint and then used canvas to draw a digital clock on top of it. You can increment or decrement the time on the clock by clicking on the up and
down arrows next to the time, and display the time with a voice recording by clicking set. The code base isn't the tidiest but hopefully is readable enough.

## How to Run

The project uses modules so you'll need to run it on a local server. I use the Live Server extension in VS Code and run through the Command Palette (F1 -> Live Server), and it
should display everything automagically. To run the tests use 'npm run test' in a terminal at the project's root. Enjoy :)

## The Challenge

Your challenge this week is to build a speaking clock. Given this sample set of 24-hour times, your clock should output a readable, English string representation of the time in 12-hour format.
:five:  Points are awarded for a working solution  
:four:  Points are awarded for a solution which can output results spoken with audio  
:one:  Point is awarded for providing a suite of unit tests  

### Example:
Given the following inputs:
14:05
17:45
Your clock might output:
It's two o' five pm
It's five forty five pm