# mimicvatAnalysis
jupyter notebook visualization of mimicvat database

I made this notebook to try out pandas/matplotlib to visualize some of the data that I've collected.

I started by importing my SQL db file and cleaning missing/non-number values. Once I did that, I started plotting my data.
The first plot I made was the converted mana cost vs power of all creatures in the game. Then, I split up the data by card color and plotted each one individually. It was interesting how each color's trajectory was different. The steaper the incline, the less efficient the color is. This makes sense, considering how efficient the color green is vs white.

I also plotted the normal price, foil price, and ratio of a card to check out what that looks like.
