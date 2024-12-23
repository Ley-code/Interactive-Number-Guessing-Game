# Interactive Number Guessing Game

This project implements an interactive number guessing game using digital logic components and Proteus simulation. It features a random number generator, a feedback mechanism, and a limited trial system to challenge and engage users.

## Project Overview
- A two-digit random number generator produces numbers between 00 and 99.
- Users have five attempts to guess the correct number.
- Feedback is provided based on the user's guesses: "Guess Higher," "Guess Lower," or "You Are Correct!"
- The game includes a trial counter, game-over logic, and a reset function for continuous play.

## Features
1. **Random Number Generation:**
   - Generates a unique two-digit number for each session.
   - Ensures randomness using a clock-driven counter.

2. **User Input Handling:**
   - Users input their guesses using switches for tens and ones place.
   - Inputs are converted to binary-coded decimal (BCD) for processing.

3. **Feedback Mechanism:**
   - Clear visual feedback using 7-segment displays and LEDs.
   - Indicates whether to guess higher, lower, or confirms the correct guess.

4. **Trial Limitation:**
   - Limits the user to five attempts to maintain gameplay balance.
   - A trial counter tracks the number of guesses made.

5. **Game Termination and Reset:**
   - Ends the game upon correct guess or after five attempts.
   - Includes a reset function to start a new game seamlessly.

## Components
- **Digital ICs:** Includes counters (IC 4017), logic gates (AND, NOT, XOR), and decoders.
- **7-Segment Displays:** For displaying random numbers, user guesses, and trial counts.
- **Clock and Timer Circuits:** Used for random number generation and guess tracking.
- **LED Indicators:** Provide feedback for user actions and game status.

## Simulation
The game is simulated using Proteus, a circuit design and simulation tool. Proteus allows for:
- Real-time testing of game logic and functionality.
- Visualization of component interactions.

## How to Run the Project
### Prerequisites
1. Install Proteus software on your computer.
2. Load the provided `.dsn` file into Proteus.

### Steps
1. **Initialize the Circuit:**
   - Flip the "Start a New Game" switch to reset the game.
2. **Input a Guess:**
   - Use switches to set the tens and ones digits of your guess.
   - The binary-coded decimal system automatically processes your input.
3. **Observe Feedback:**
   - View hints on the 7-segment display and LEDs.
   - Adjust your next guess based on the feedback provided.
4. **End of Game:**
   - Either guess the correct number or exhaust five trials to end the game.
5. **Reset:**
   - Use the reset switch to start a new game session.

## Future Enhancements
- Incorporate a sound-based alert system for game feedback.
- Add multi-digit random number support for increased difficulty.
- Optimize logic circuits for lower power consumption.

## License
This project is for educational purposes and is open for contributions.
