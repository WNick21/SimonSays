# SimonSays
EE339 Simon Says Project Code
This is the code for EE339. The project is meant to replicate the game Simon Says. A random
sequence must be generated, then the user must memorize the sequence in increasingly large numbers
and correctly input them into the game. LEDs and tones will be used to display the sequence to 
the user. As per the instructor the random sequence only has to be 16 digits long. The digits
we plan to use will be a combination of 1, 2, 4, and 8 because those numbers map to a binary
0b00000001, 0b00000010, 0b00000100, and 0b00001000 which makes interfacing with the switches
and LEDs easier.

Once the game ends after the user has put in the wrong sequence the game should falsh some
sort of sequence and indicate how many correct inputs the user got based off of how many times the
LED flashes and the tone sound.
