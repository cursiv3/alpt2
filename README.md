# JavaScript-Vector-Drawing-App
Programming Challenge

Vector drawing that given bytecode will log pen moves accordingly.
Pen is restricted to a certain area, and the pen should lift when
it leaves the area, then move back to a "down" position when it re-
enters the page so long as the last command was still to draw.

Bytecode is as follows:

Commands:
F0 - clear the drawing, reset workspace
A0 - Set Color, A0 must be followed by 8 bytes of hex values for color
C0 - Move pen, C0 followed by N number of pairs (X and Y)
80 - Pen up/down control

To Install:

mkdir js-draw-app
git clone <this repo url>
cd JavaScript-Vector-Drawing-App
npm i
npm run start