# PyDeck

**PyDeck** is a simple, interactive Python-based card game inspired by Blackjack. It simulates a card-dealing game where you play against a computer opponent, trying to get as close to 21 as possible without going over.

## Skills Demonstrated

### Core Python Concepts:
- **Random Module**:
  - Used for simulating card draws from a deck using the `random.choice` function.
- **Data Structures**:
  - **Lists**: 
    - Used to represent a player's hand and the computer's hand (e.g., `user_cards`, `computer_cards`).
    - Dynamic updates as cards are added or replaced during the game.
- **Built-in Functions**:
  - **`sum()`**: 
    - Efficiently calculates the total score of the cards in a player's or computer's hand.
  - **`range()`**: 
    - Used to control the initial card dealing process, ensuring two cards are dealt at the start.
- **Functions**:
  - Modularized functionality for tasks like dealing cards (`deal_card`), calculating scores (`calculate_score`), and comparing results (`compare`).
- **Conditionals**:
  - Implements game logic to handle scenarios like Blackjack, busts, and draws.
- **Loops**:
  - Ensures the game flow with `while` loops, allowing the player to draw additional cards or pass.
- **Input/Output**:
  - Interactive prompts guide the user through the game with real-time updates on their hand and score.

## How to Play

1. Launch the game by running the script.
2. Follow the prompts:
   - You are dealt two cards, and so is the computer.
   - Choose whether to draw another card or pass.
   - The computer will draw cards until its score is at least 17 or it gets a Blackjack.
3. The game will calculate the final scores and declare the winner.

## Example Output

```
Do you want to play a game of PyDeck? Type 'y' or 'n': y

Your cards: [10, 9], current score: 19
Computer's first card: 6
Type 'y' to get another card, type 'n' to pass: n

Your final hand: [10, 9], final score: 19
Computer's final hand: [6, 9, 2], final score: 17
You win!
```

## Game Rules
- **Blackjack**: A score of 21 with the first two cards (Ace + 10/face card) is an instant win.
- **Bust**: If the total score exceeds 21, the player loses.
- **Computer Strategy**: The computer continues to draw cards until its score is at least 17, unless it gets a Blackjack or busts.

## About Me
**A. RAHMAN** - Python Developer & Gaming Enthusiast