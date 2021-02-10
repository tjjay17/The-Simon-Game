# The-Simon-Game (Currently only a desktop version)
An implementation of the Simon Memory Game.
https://tjjay17.github.io/The-Simon-Game/

![SimonGame](https://user-images.githubusercontent.com/56407501/107498782-32e88b80-6b62-11eb-8bdb-3a552b727b85.gif)


The game starts by prompting a user to press a key to begin.
It will then flash one of the four colors (Blue, Yellow, Red or Green) and make a sound based on the color.

The player will then have to click on the color that was just flashed. If the user presses the right color, then another color will be flashed. The user must then click the pattern from the beginning. The game keeps going that way, flashing a new color with the player having to replicate the sequence from the start.

# EXAMPLE 

You begin to play, and it flashes blue.

Then you hit blue. 

It then flashes red. 

You press blue,then red. 

Then it flashes green.

You press blue, red then green.

Then it flashes red.

You press blue,red,yellow,green.

YOU LOSE! It was supposed to be blue, red, green, red.

You are essentially just building on the pattern each time.
