WATER TANK GAME

A command-line strategy game where players compete to fill their water tanks using a combination of water and power cards. Outsmart your opponent by managing your cards wisely and utilizing special abilities!

CONTENTS
- Installation
- How to Play
  - Game Rules
  - Card Types
  - Turn Mechanics
- Features
- Game Flow
- AI Strategy

INSTALLATION

1. Ensure Python 3.x is installed
2. Clone the repository:
   git clone https://github.com/yourusername/water-tank-game.git
3. Navigate to the project directory:
   cd water-tank-game
4. Run the game:
   python water_tank_game.py

HOW TO PLAY

GAME RULES
- Players start with 0 water in their tanks
- First player to reach 75-80 water wins
- Tanks overflow if exceeding 80 (e.g., 85 becomes 75)
- Each turn: Use or discard 1 card, then draw a replacement

CARD TYPES
Water Cards:
1  - Add 1 water
5  - Add 5 water
10 - Add 10 water

Power Cards:
SOH - Steal half opponent's water
DOT - Drain opponent's tank to 0
DMT - Double your current water

TURN MECHANICS
1. Choose to Use or Discard a card
2. Select card from your hand
3. Automatically draw replacement card
4. Cards are automatically sorted: Water (sorted) then Power (alphabetical)

FEATURES
- Dynamic card shuffling and pile replenishment
- Overflow simulation for realistic water management
- Computer opponent with strategic AI
- Input validation and error handling
- Real-time tank status updates

GAME FLOW

Human Turn:
1. View current water levels
2. Choose action (Use/Discard)
3. Select card
4. Apply card effect
5. Draw replacement card
6. Check win condition

Computer Turn:
1. AI evaluates optimal move
2. Executes action automatically
3. Updates game state
4. Checks win condition

AI STRATEGY
The computer opponent prioritizes:
1. Immediate winning moves
2. Maximum water gain combinations
3. Opponent disruption (DOT/SOH)
4. Discarding low-value water cards

Example AI Decision Process:
1. Check for direct win cards
2. Calculate potential gains for all cards
3. Choose highest value action
4. Fallback to discarding if no beneficial moves

TIP: Watch the computer's discard patterns to anticipate their strategy!
