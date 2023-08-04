# Zombie Survival
 A simple python text-based game of survival, resource management and strategic deision making.

 [See Code](https://github.com/tophercollins/zombie-survival)

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
* Created 3 personality identities of generous, cautious & greedy to create variety in computer decision.
** Generous - Always give all their resources to the camp at the end of the day
** Cautious - Always keeps 1 of each resource
** Greedy - Always keeps 2 of each resource
** Combative - Always tries to keep the highest weapon score out of all players

 ## Game Features

This project is a simulation of a survival resource management game, implemented using rule-based mechanics. In this game, players, starting with minimal resources, must strategically explore a variety of locations to scavenge food, medicine, and weapons, the three key resources in the game.

Each day players embark on missions of varying difficulty to collect these resources, with outcomes determined by dice rolls. At the end of each day, food tokens must be consumed for survival and potential zombie attacks or health issues need to be dealt with using the resources. Player and camp health states are central to the game dynamics, impacting player capabilities and resource utilization.

The system follows the sequence of players' actions, evaluates the consequences, and manages the game state including player health, camp resources, and daily events. The design encompasses aspects of randomness and decision-making, reflecting the unpredictable nature of survival scenarios and the importance of strategic planning.

[See Code](https://github.com/tophercollins/zombie-survival)
