This Java code represents a card deck management system with a user-friendly interface. The Card class defines a standard playing card with attributes such as rank and suit, offering methods for retrieving these attributes and implementing the Comparable interface for sorting. The Deck class utilizes a vector to create, shuffle, and display a deck of cards. The system provides functionalities such as drawing a random card, emptying the deck, printing a specific card, sorting the deck, comparing two random cards, checking if two cards are the same, finding a card by its rank and suit, and dealing a hand of cards. The interactive menu-driven startMenu method allows users to perform these actions by selecting options, ensuring a dynamic and engaging card deck manipulation experience. The program is designed to handle edge cases, such as attempting to draw from an empty deck or shuffle an already empty deck. Overall, the code serves as a comprehensive and interactive implementation of a playing card management system.

Deck Class:

    1. createDeck(): Initializes a deck of 52 cards with ranks ranging from Ace to King and suits (Hearts, Diamonds, Clubs, Spades).
    
    2. displayDeck(): Prints the cards in the current deck or informs the user if the deck is empty.
    
    3. shuffleDeck(): Shuffles the cards in the deck, ensuring a random order.
    
    4. drawCard(): Randomly draws a card from the deck, removing it, and displays the drawn card along with the updated deck size.
    
    5. emptyDeck(): Clears the entire deck, making it empty.
    
    6. printCard(): Prompts the user for an index and prints the card at that index in the deck if it exists.
    
    7. sortCard(): Sorts the deck based on card ranks in ascending order.
    
    8. compareCard(): Compares two randomly selected cards in the deck and prints whether one card is higher, lower, or equal in rank to the other.
    
    9. sameCard(): Checks if two randomly selected cards in the deck have the same rank and informs the user of the result.
    
    10. findCard(String suit, int rank): Searches the deck for a card with a specified suit and rank and informs the user whether the card is present.
    
    11. dealCard(): Deals a hand of 5 cards from the deck, removing them, and prints the dealt cards.

Card Class:

    1. compareTo(Card other): Implements the Comparable interface to allow sorting cards based on their ranks.
    
    2. toString(): Overrides the toString method to provide a human-readable representation of a card.

Main Class:

    1. startMenu(): Implements a console-based menu system where users can choose various operations on the deck, such as displaying, shuffling, drawing, emptying, printing, sorting, comparing, checking sameness, finding by rank and suit, dealing a hand, or quitting the game.

Main Method:
    
    1. main(String[] args): Initiates the card game by creating a deck and launching the menu system for user interactions.
