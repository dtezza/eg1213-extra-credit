# EG1213 - Extra Credit Assignment

## Exercise 1

Modify the poker.c program of Section 10.5 by moving the num_in_rank and num_in_suit arrays into main, which will pass them as arguments to read_cards and analyze_hand.

**commit this exercise with the message "Exercise 1 submission"**

## Exercise 2

Remove the num_in_rank, num_in_suit, and card_exists arrays from the poker.c program of Section 10.5. Have the program store the cards in a 5x2 array instead. Each row of the array will represent a card. For example, if the array is named hand, then hand[0][0] will store the rank of the first card and hand[0][1] will store the suit of the first card. 

**commit this exercise with the message "Exercise 2 submission"**

## Exercise 3

Modify the poker.c program of section 10.5 by having it recognize an additional category, "royal flush" (ace, king, queen, jack, ten of the same suit). A royal flush ranks higher than all other hands. 

**commit this exercise with the message "Exercise 3 submission"**

## Exercise 4

Modify the poker.c program of Section 10.5 by allowing "ace-low" straights (ace, two, three, four five). 

**commit this exercise with the message "Exercise 4 submission"**
