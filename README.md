# Arduino Memory Game

## Introduction

Welcome to the Arduino Memory Game repository! This game is designed to test and improve your memory skills using LED lights and buttons. Players have to remember a sequence of LED lights and then replicate it using the corresponding buttons. As the game progresses, the sequences get longer and more challenging.

## Features

- Multiple levels to play
- Count-down before game starts for readiness
- Dynamic difficulty options: Easy and Hard
- Time limit for input to add an extra challenge
- Visual and audio feedback via LED and buzzer
- LCD screen to display time and messages

## Components Used

- Arduino board
- 4x LEDs
- 4x Push buttons
- LCD Screen (16x2)
- Buzzer

## How to Set Up

1. Clone this repository.
2. Set up your Arduino board and connect all the components according to the circuit diagram provided.
3. Upload the Arduino code to your board.

## Libraries Used

- LiquidCrystal.h for LCD screen management

## Gameplay

1. Choose the difficulty level by pressing the blue or red button.
2. The game will show a sequence using the LEDs.
3. Players must replicate the sequence using the buttons.
4. Game over if the wrong sequence is inputted or time runs out.

## Code Overview

- The main loop generates the pattern, displays it, and then waits for the player input.
- The patterns are stored in arrays, and the game checks the user input array against the generated pattern.
- Difficulty levels are adjusted with different time limits and levels to start with.

## Troubleshooting

If you encounter any issues:
1. Make sure all components are correctly connected.
2. Double-check the pin numbers in the code.
3. Make sure the Arduino board is properly powered.

## Future Enhancements

- Adding more complex patterns.
- Score-keeping functionality.
