The code demonstrates a simple card game simulation with a deck of cards and various operations that can be performed on the deck. 

Deck Class:
    createDeck(): Initializes a deck of 52 cards with ranks ranging from Ace to King and suits (Hearts, Diamonds, Clubs, Spades).
    displayDeck(): Prints the cards in the current deck or informs the user if the deck is empty.
    shuffleDeck(): Shuffles the cards in the deck, ensuring a random order.
    drawCard(): Randomly draws a card from the deck, removing it, and displays the drawn card along with the updated deck size.
    emptyDeck(): Clears the entire deck, making it empty.
    printCard(): Prompts the user for an index and prints the card at that index in the deck if it exists.
    sortCard(): Sorts the deck based on card ranks in ascending order.
    compareCard(): Compares two randomly selected cards in the deck and prints whether one card is higher, lower, or equal in rank to the other.
    sameCard(): Checks if two randomly selected cards in the deck have the same rank and informs the user of the result.
    findCard(String suit, int rank): Searches the deck for a card with a specified suit and rank and informs the user whether the card is present.
    dealCard(): Deals a hand of 5 cards from the deck, removing them, and prints the dealt cards.

Card Class:
    compareTo(Card other): Implements the Comparable interface to allow sorting cards based on their ranks.
    toString(): Overrides the toString method to provide a human-readable representation of a card.

Main Class:
    startMenu(): Implements a console-based menu system where users can choose various operations on the deck, such as displaying, shuffling, drawing, emptying, printing, sorting, comparing, checking sameness, finding by rank and suit, dealing a hand, or quitting the game.

Main Method:
    main(String[] args): Initiates the card game by creating a deck and launching the menu system for user interactions.
