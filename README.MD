# Poker Hand Evaluator
A Python program that simulates a standard 52-card deck, deals a 5-card hand, and identifies the best poker hand. Built with Python's standard library.

## Features
- Initializes and shuffles a full 52-card deck
- Displays the deck in a formatted 4-column layout
- Deals a 5-card hand from the top of the deck
- Evaluates and returns the best poker hand (Royal Flush down to High Card)

## Requirements
```
Python 3.x
```

## Usage
```bash
python poker_hand_evaluator.py
```

## Example Output
```
----------------------------------------------------------------------------------------------------
YOUR CARDS:
----------------------------------------------------------------------------------------------------
Seven of Diamonds    King of Diamonds     Five of Spades       Eight of Clubs       Seven of Clubs
----------------------------------------------------------------------------------------------------

The best hand you have is One Pair.
```

## Hand Rankings
Hands are evaluated from highest to lowest:
- Royal Flush
- Straight Flush
- Four of a Kind
- Full House
- Flush
- Straight
- Three of a Kind
- Two Pair
- One Pair
- High Card

## Known Issues
- No interactive card drawing or swapping
- Deck output assumes exactly 52 cards printed in groups of 4
