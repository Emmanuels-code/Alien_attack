# alien_attack
Alien Attack Simulator
=====================================
Overview
This JavaScript project simulates an alien attack scenario where alien ships engage in combat. The code defines a Ship class and a utility function createAlien to generate alien ships with random attributes.
Installation
To use this code, simply clone the repository and include the Ship.js and utils.js files in your project.
Usage
Ship Class
The Ship class represents a space ship with the following properties:
hull: The ship's health points.
firepower: The damage dealt by the ship's attacks.
accuracy: The probability of a successful attack (between 0 and 1).
Methods
attack(target, updateMessage): Attacks a target ship, dealing damage if successful.
takeDamage(amount): Reduces the ship's hull by the specified amount.
Creating Alien Ships
The createAlien function generates a new alien ship with random attributes:
hull: Between 3 and 6.
firepower: Between 2 and 4.
accuracy: Between 0.6 and 0.8.
