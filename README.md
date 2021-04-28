# Metagame prediction for MTG

This project aims to anticipate the metagame (the popularity of the various deck archetypes), using data about the metagame of the current and past weeks.

To use this algorithm : the data you input (in the pandas.read) needs to be an excel table formatted in the following way : 

One line is one week of data;

The columns : the first column is the number of the week; the others are organised in 16 groups of 18 (one for each deck, the 'others' category is made of all the decks that did not fit in one of the archetypes), as follows : 
    The first column of the goup is the popularity of the deck;
    The second is its global winrate;
    the other columns are its winrate against the decks (including itself).
