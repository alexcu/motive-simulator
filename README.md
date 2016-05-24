# Motive Simulator

This code is adapted from Don Hopkins' article [The Soul of The Sims](http://www.donhopkins.com/home/images/Sims/) which shows an prototype of the 'soul' of what became The Sims 1, written January 23, 1997. It is based off the images provided in the article (see the attach PDF) sticking to the main adaptation of Wright's simulation models, only modified to make it visualised with a few minor adaptations to make it run.

Thought it would be fun to implement it, run the simulation, and what do you know it does kind of look like a basic foundation to The Sims 1's needs system!

If you'd like to run it or play around with it, you can compile using `gcc motives.c -o motives`.

## Original Article

Here's an original copy of the article:

>
```
The Soul of The Sims, by Will Wright 
Macintosh HD:XmotiveHarness:src/Motive.c 
Tuesday, January 28, 1997 / 9:25 AM
```
> This is the prototype for the soul of The Sims, which Will Wright wrote on January 23, 1997.
> 
> I had just started working at the Maxis Core Technology Group on "Project X" aka "Dollhouse", and Will Wright brought this code in one morning, to demonstrate his design for the motives, feedback loop and failure conditions of the simulated people. While going through old papers, I ran across this print-out that I had saved, so I scanned it and cleaned the images up, and got permission from Will to publish it.
> 
> This code is a interesting example of game design, programming and prototyping techniques. The Sims code has certainly changed a lot since Will wrote this original prototype code. For example, there is no longer any "stress" motive. And the game doesn't store motives in global variables, of course.
> 
> My hope is that this code will give you a glimpse of how Will Wright designs games, and what was going on in his head at the time!
>
> _- Don Hopkins_

## Demo

![Demo](https://raw.githubusercontent.com/alexcu/motives-simulator/master/demo.gif)
