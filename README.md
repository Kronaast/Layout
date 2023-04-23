# Layout
Hello everybody, this is the layout i developed for my videos,

for more in detail explanation please watch this video: https://youtu.be/mAuMHT9-b20

Assuming that i did not select the wrong license you are free to download the code and edit it yourself and/or use it in any way you want, you can republish it too but at least change a few things.

I am going to put here a quick summary of how to use the layout:
all the variables must be all lower case
- the variable "pokemonName" must be the name of the species of whatever pokemon you are using;
- the variable "game" must be the name of the game that you are playing, copy the values in the comments above it if you are unsure;
- the variable "enableImg" allows you to chose wheter to use no image, the one in the pictures folder or the sprite based on the game
- lastly "movesZoom" and "statsZoom" handle the dimensions of the table with the moves on the right and the table of the stats on the bottom left respectively
- both the pokemon iamge if set to manual and the background image can be customized by overwriting the ones already present in the Pictures folder

Known Bugs/limitations:
- PP ups are not counted, will fix it in the future (should be fixed)
- The layout does not work if you change pokemon mid-run
- The layout is using the newer amount of pp for moves (barrier is 30 pp in emerald, 20 past x/y)

Future developments:
- PP ups handling
- dispay IV/EV
- display current location
- indicator for physical or special move 

Future code improvements:
- moving style part to css
- moving print stuff to functions
- more comments
- function contracts
