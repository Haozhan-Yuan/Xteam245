# Xteam245
Team Members:
Gabriel Kim Wilkinson, Haozhan Yuan, Russell Cheng, Nada Elkordi

"Classic Solitaire Game"

Solitaire is a single-player game in which a player sorts cards into 'piles' based upon their suit and value. The objective is to eventually sort all cards into a pile, thereby completing the game.

Cards are ranked as follows:
King(high),Queen, Jack, 10, 9, 8, 7, 6, 5, 4, 3, 2, (low)

Cards have two colors: red and black

The game is won when the player builds four piles for each suit: Hearts, Diamonds, Spades, and Clubs.

The sorted piles are called foundations

A full card set is psrtitioned as follows: 
1- The Tableau: Seven piles that start face down 
2- The Foundation: Initially, empty four piles for each suite
3- The Hand Pile: The remaining cards that are not in the Tableau. Initially face down.
4- The waste pile: Contains cards that cannot be placed in any of the above piles.
 
Our application will uses a series of classes representing the different piles of cards in a solitaire game. These utilize a base Pile class, which the additional classes extend, as well as a Card class which models cards and provides information on their suit, value, and current status.

The GUI of this program will provided players with a visually pleasing interface for the game.
