# Gameplay
_but from the technical side!!_

## Chart
The chart is represented as a series of (scaled?) collision blocks, with block IDs corresponding to their color, and a graphical representation.
The blocks will all be set to one group, and will move along the playfield.

## Input
The input works by toggling on and activating a series of collision blocks, corresponding to the timing windows (scale yet to be determined),
and simultaneously checking the overlaps between the chart collision block and timing blocks, logically similar to an if-else chain.
Currently I have no intention of creating an anti-mash system, except for very early/late hits (i.e. outside of hit judgement zone).

## Scoring/combo
A combo counter will be kept during the gameplay part, incremented for every non-miss hit, and set back to 0 for each miss.
On top of that, the if-else chain overlap checking will increment the counters for each corresponding judgement.
I might possibly also add an accuracy counter - maybe not percentage-based, but fraction-based
    (i.e. denominator is constant/equal to max score, enumerator increases with each hit).

## Score bar
Right above the playfield will be a horizontal bar, showing the player's progress, as in whether they are clearing the chart or not,
moving to the right with each non-miss hit. At the end will be a collision block, that will detect whether the bar is showing a clear
    (which will also have a big collision block in its zone).
If, at the end of the song, the end of the bar is in the clear zone, the song is cleared.
Else, the song is failed.
