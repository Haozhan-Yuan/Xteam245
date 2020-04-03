# Xteam245
Team Members:
Gabriel Kim Wilkinson, Haozhan Yuan, Russell Cheng, Nada Elkordi

"Classic Solitaire Game"

Solitaire is a single-player game in which a player sorts cards into 'piles' based upon their suit and value. The objective is to eventually sort all cards into a pile, thereby completing the game.

Cards are ranked as follows:
King(high),Queen, Jack, 10, 9, 8, 7, 6, 5, 4, 3, 2, Ace(low)

Cards have two colors: red and black

The game is won when the player builds four piles for each suit: Hearts, Diamonds, Spades, and Clubs.

The sorted piles are called foundations

A full card set is partitioned as follows: 
1- The Tableau: Seven piles that start face down, with the top card face up. The seven piles are of size 1 through 7, ascending. 
2- The Foundation: Initially, empty four piles for each suite
3- The Hand Pile: The remaining cards that are not in the Tableau. Initially face down.
4- The waste pile: Contains cards that cannot be placed in any of the above piles.
 
Our application will uses a series of classes representing the different piles of cards in a solitaire game. These utilize a base Pile class, which the additional classes extend, as well as a Card class which models cards and provides information on their suit, value, and current status.

The GUI of this program will provided players with a visually pleasing interface for the game.

Description of Rules:
1. Each suit in the foundation should start with the lowest rank (1).
a. Cards are added to the foundation pile in ascending order of their
rank.
2. Only a face down card from the tableau can be opened with a click to be
face up.
3. You can move a face up card from one tableau pile (Card 1) to another
tableau pile with (Card 2) if the following conditions apply.
 (1) Card 1 is of different color from Card 2
 (2) Card 1 is of a rank that is one less than the rank of Card 2.
4. If a tableau pile is empty, you can move a face up King card to this tableau
pile.
5. When there are no moves possible among the foundation piles, the player
can open a card from the hand pile into the waste pile and put it under a
tableau pile.
6. A card can go directly from the hand pile to any of the foundation piles.
7. The game ends when all cards are sorted into the foundation pile.
 
The Data Structure that will be used in this project is:
1- Stack ADT: every pile of cards will be represented by a stack
2- Integers variable: Card Dimensions(width and height)
3- Enum variables for Card suit, rank, and color.

The classes used in the design are:

1-Class Card
	Represents the main class of the program.
	It will contain: Variables of card dimensions(xlocation, ylocation), card suit, color, and rank.
2-Class Pile
	Every pile will be represented using a stack ADT
	PileNode will be inner class to represent every stack node

4-Class WastePile
5-Class HandPile
6-Class Tableau
7-Class SolitaireGame


Milestone1: Initialize GUI class, assemble library images and other prerequisites

Milestone 2: Implement classes Card, Pile, FoundationPile, WastePile, HandPile, and Tableau

Milestone 3: Implement the game logic in class SolitaireGame(class with the main method)

Milestone 4: Implement graphical changes and events based on user input
Note: The repository contains a PDF Document with details of the design specification, as well as a PowerPoint presentation providing the information in an alternate format.
