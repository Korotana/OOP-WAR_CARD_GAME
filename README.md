# OOP-WAR_CARD_GAME

 This card game will be the card game "War" for two players, you an the computer. 
If you don't know how to play "War" here are the basic rules:
The deck is divided evenly, with each player receiving 26 cards, dealt one at a time,
face down. Anyone may deal first. Each player places his stack of cards face down,
in front of him.

The Play:

Each player turns up a card at the same time and the player with the higher card
takes both cards and puts them, face down, on the bottom of his stack.

If the cards are the same rank, it is War. Each player turns up three cards face
down and one card face up. The player with the higher cards takes both piles
(six cards). If the turned-up cards are again the same rank, each player places
another card face down and turns another card face up. The player with the
higher card takes all 10 cards, and so on.

Ignore "double" wars

https://en.wikipedia.org/wiki/War_(card_game)

# Technologies Used
# Python - 3.9.8

the Python program simulates the "War" card game by implementing object-oriented principles and utilizing core data structures and functions:

    Classes and Object-Oriented Design:
        Deck Class: Responsible for generating a deck of cards (a combination of suits and ranks). It provides methods for shuffling the deck (shuffle()) and splitting it into two halves (split_in_half()).
        Hand Class: Represents the hand of each player. It has methods for adding (add()) and removing cards (remove_card()) from the player's hand and outputs the number of cards remaining.
        Player Class: Models the player behavior, including playing a card (play_card()), removing cards for "war" scenarios (remove_war_cards()), and checking if the player still has cards left (still_has_cards()).

    Data Structures:
        The Deck class uses list comprehensions to create the deck of cards, which are stored as tuples ((suit, rank)).
        List: The core data structure used for storing and managing the cards in both the Deck and Hand classes.
        shuffle() from random: Randomizes the order of the cards to simulate shuffling.

    Game Logic:
        The game operates using a while loop that continues until one player runs out of cards.
        Each round involves both players drawing one card, and their ranks are compared to determine the winner. If the ranks are tied, a "war" occurs, requiring additional cards to be drawn.
        Card comparisons are based on the index of the ranks in the predefined RANKS list, which allows for efficient rank-based comparisons.

    Event Handling:
        The program captures key game events, such as card drawing, war conditions, and win/loss scenarios, and dynamically adjusts the state of the game by manipulating the table_cards list.

    Input and Output:
        The user provides their name via input, and game progress is output using print() statements, showing round status, card counts, and war occurrences.

Overall, the code demonstrates concepts like encapsulation, inheritance, and dynamic list manipulation, while efficiently managing game flow using loops and conditionals.


**How To Run**
# Just install and run on your favourite IDE.
