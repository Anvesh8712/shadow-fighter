# shadow-fighter

This project is a 2D Fighter game implemented using pure JavaScript, with characters and scenarios rendered on HTML Canvas.

## Description

The code snippet creates a 2D canvas for a fighting game. There are two characters, 'player' and 'enemy', each with different sets of images for various actions. The game handles the collision, attacking, and health logic for these characters.

## Getting Started

To run this code on your local machine, simply include the script in your HTML file. This code assumes you have images located at the provided './img/' directory.

## Code Overview

The following points provide a brief overview of the code:

- **Canvas:** The canvas is set up with a width of 1024px and height of 576px.
- **Sprites:** The code creates different sprites, such as 'background', 'shop', 'player', and 'enemy', each with a set of images for various states like idle, run, jump, etc.
- **Gravity:** There is a gravity constant which presumably is used in the game physics (though it's not shown in the provided code).
- **Movement:** The script handles user input to control the characters' movements and attacks.
- **Collision and Attacks:** The game logic checks for collisions between characters and changes the state of the game accordingly.
- **Health Management:** The characters' health is managed, and the game state checks to see if any character's health drops to zero.

Remember to include GSAP library as it is used to animate health bar changes.

## Dependencies
This project assumes the following dependencies:

- The GSAP library for animations.
- Images located in the './img/' directory.

## Usage

The game can be controlled via the keyboard. The following keys are used:

- Player:
  - 'a': move left
  - 'd': move right
  - 'w': jump
  - ' ': attack
- Enemy:
  - 'ArrowLeft': move left
  - 'ArrowRight': move right
  - 'ArrowUp': jump
  - 'ArrowDown': attack
