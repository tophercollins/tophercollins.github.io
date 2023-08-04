# Zombie Survival [See Code](https://github.com/tophercollins/zombie-survival)
 A simple python text-based game of survival, resource management and strategic deision making.

## Game Overview
Zombie Survival is a game designed for 1 to 4 players, where each player is a member of a camp collecting resource and fighting against zombie attacks.
The objective is survive for ten days by gathering resource on scavenging missions during the day and defending against zombie attacks during the night.
Any players remaining at the end of the ten days win.

## Programming
The game was built using fundamentals of Object-Orientated Programming.
Models are created for Players, Locations and Camp which each inherits resource attributes from an overall GameEntity class and then adds specific attributes for each class. 
Design operates from small functions for gameplay mechanics, larger functions to operate the 4 main stages of gameplay and a master function to runs the game loop.

### Computer Players & Decision Making
Analysing Best Choices
* Introduced best_resource() and best_location() functions utilising built-in Python getattr() to judge which is optimal resource to collect. 

Randomness
* Integrated a random component to computer decisions so they are not always playing optimal

Computer Player Personalities
* Created different personality to create variety in computer decisions (generous, cautious & greedy).
