# Tactical-Chaos






<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/carolha2">
    <img src=https://icons.veryicon.com/png/o/object/color-game-icon/character-3.png alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Tactical Chaos</h3>

</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#game-environment">Game environment</a></li>
        <li><a href="#first-nine-rounds">First nine rounds</a></li>
        <li><a href="#after-the-ninth-round">After the ninth round</a></li>
      </ul>
    </li>
    <li>
      <a href="#built-with">Built With</a>
    </li>
    <li><a href="#diagram">Diagram</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

A strategic board game where players try to eliminate their opponents' champions in turn-based gameplay.

In our game, each turn consists of two steps:
1) planning step where the players buy champions and give them orders.
2) execution step of the players’ plans.

Each player will build a team by buying champions from the store. We will divide the game into two
phases. The first nine rounds are phase one. Where the players place their champions on the map. The
second phase will be run automatically by executing the player’s plans.
The game will end after N rounds, or when only one player’s champions remain in the arena.

#### Game environment
* Board game (100X100) squares;
* Up to 8 players;
* Each player will have up to 9 champions in the arena;
* In each round, the player can buy champions from a limited temporal store (5 random champions from the complete champions list will be updated each round);
* Buying the same champion 3 times will promote him/her to level 2;
* Having 3 copies of the level 2 champion will promote him/her to level 3 (max level);
* Each champion belongs into 2/3 classes;
* Assembling champions that belong to the same class will grant the team (player’s champions)
additional abilities (see appendix 2);
* Each player has a bench that can keep up to 8 champions;
* The planning phase has limited time; players must decide their actions within that time.
* At the beginning of each round, all players will receive 2 golden coins;

#### First nine rounds
* In the first 9 rounds, players will buy and put champions in any square on the map;
* Other players' champions will be hidden;

#### After the ninth round
* Each player can buy and sell champions (based on their price);
* Each player can select any number of his champions on the battlefield and give him/her an order:
	o Move in a specific direction;
	o Attack a specific enemy (if the enemy is in the champion's range);
	o Use the ability (if it’s available);
* Each round will have a new order for the players to take action;
* In the planning phase, the player can swap between champions on the bench and the arena; players can swap up to two champions;
* At the end of the planning phase, the game will calculate the players’ classes and buff their teams with the appropriate classes buffs;
* When a champion dies, he/she will be excluded from the game and the player will lose his buff (from the classes);
* When a champion dies, his/her owner team size will be decreased by one.
  






<!-- BUILT WITH -->
### Built With

<img src=/java.png alt="Logo" width="80" height="80">


<!-- DIAGRAM -->

### Diagram

![](/class%20diagram.png)







