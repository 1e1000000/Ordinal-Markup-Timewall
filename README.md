# Ordinal Markup Expert
get to work lazy
A game of maximizing ordinals and decreasing numbers

FILE OVERVIEW:<br>
`calc.js` will contain all of the get() and calc() functions that get the value of something.<br>
`saveload.js` will contain initiation, saving, and loading files.<br>
`color.js` will contain functions relating to the conversion of colors and the color of the ordinal.<br>
`script.js` will contain all other stuff.

Add more.

# Changes from Vanilla OM

## Pre Booster
Factor cost scaling harsher (^2, ^3, ^3, ^4, ^4, ^8, ^36)<br>
Factor Shift cost is higher (1000, 1e4, 1e6, 2e10, 1e14, 1e23, 1e103)<br>
Dynamic increase 20x slower and cap 3.33x lower<br>
In Factor Shift 7, Tier 1 automation click 2x slower<br>

## Booster
### Pre-Challenges
You can't bulk factor boosts until unlock Incrementy<br>
Couple Booster Upgrade cost changed<br>
Tier 2 automation click 2x slower<br>
Reduce Boosters boost to 5+x^0.6<br>
You gain passive OP from Booster Upgrade 7 2x slower<br>
### Challenges
Unlock Challenge require 20 unspent boosters<br>
Couple Challenge goal changed<br>
You can't Manual Click in Challenge 1<br>
Increase Free factor from Booster Upgrade 11 to sqrt(Factor Boosts+1), capped at 5<br>
### Incrementy
Unlock Incrementy require 45 unspent boosters and 4 challenge completion<br>
Reduce Incrementy Upgrade 3 cost scaling to 1e7x<br>
Base Incrementy production become ^0.85, after FB24 will be ^0.9<br>
Remove challenge buff of Challenge 3<br>
### Manifold
Reduce All non-repeatable Incrementy Upgrade cost<br>
Incrementy Upgrade 7 is buffed to 1000x<br>
Reduce Manual Click limit in Challenge 6/7 to 100<br>
You can only do 25 Factor Boosts until collapse<br>

## Collapse
First Sluggish Milestone require is reduce to 25 (may even 24 that make first collapse not possible get this milestone)<br>
You gain Refund Point 600x slower (may even slower)<br>
