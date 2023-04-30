# Aloft
A lightweight strategy game about hot-air ballooning. During the game you will oversee a mass ascension at a balloon festival and try to ensure that your balloons end up in the best positions in the resulting formation.

## Overview
Aloft is a game for one to five players. It can be played in about thirty minutes and is intended for players who are at least eight years old.

During the game, you will launch a flight of hot-air balloons. You will try to ensure that your balloons end up in the best positions in the resulting formation.

## Components
  - 13 balloon cards
     - 10 regular balloon cards
     - 3 special shape balloon cards
  - 13 scoring tokens
  - 5 truck cards
  - 5 color cards
  - 1 game board

<!-- The number of special shape cards, truck cards, and scoring tokens that you will use in your game depends on how many people are playing. See the table below for details. Notice that you will always use all of the regular balloon cards and colour cards but, unless you are playing a five-player game, you will not use all of the special shape cards, truck cards, or scoring tokens. If you are playing with less than five players, you should use the scoring tokens numbered 1-12.

| Player Count | 1 - 4 | 5 |
| ----------: | ---: | ---: |
| Regular Balloon Cards | 10 | 10 |
| Special Shape Cards | 2 | 3 |
| Truck Cards | 5 | 6 |
| Colour Cards | 5 | 5 |
| Scoring Tokens | 12 | 13 |  -->


## Set Up
  1. Deal one color card at random to each player. Do not reveal this card to the other players until the end of the game.
     <!-- - Each regular balloon card is affiliated with two of the five possible colours.  The colours that a balloon card is affiliated with are the colours of the envelope of the balloon depicted on that card. Special shape cards are not affiliated with any colour.  -->
  2. Place the launch-zone truck cards in a single row below the four leftmost columns of the game board. 
  3. Place the safety truck card below the leftmost launch-zone truck card.
  4. Collect the regular balloon cards and special shape cards that you will use during your game. These cards will comprise the _balloon deck_.
  5. Display the balloon cards in a single row below the launch zone. 
  6. Place the scoring tokens nearby for use when scoring at the end of the game.
![Set up for a four-player game.](set_up_diagram.jpg)

## Gameplay
On your turn, you will perform either one or two actions:
  1. If at least one balloon is flying, move a truck.
  2. Advance a balloon.

The game ends when the lead truck moves past the rightmost column of the game board.
If this happens on your turn, you should advance a balloon as usual and then proceed to scoring.


### Move a Truck
If any balloons are flying, then before you advance a balloon you will move a truck. Trucks always move from left to right. 

When you move a truck, you will do one of the following:
  - Move a launch-zone truck.
  - Move the safety truck.

The safety truck must always be between (or even with) the lead truck and the last truck. 

#### Moving a Launch-Zone Truck
If the truck cards are in adjacent columns, then you should move the rightmost truck one column to the right.

![Moving a truck when the trucks are in a single group and the safety vehicle is centered on the launch zone.](wind_diagram_1.jpg)

Otherwise, the launch-zone trucks will be in two groups which are separated by one empty column. You should slide the rightmost truck from the first group one column to the right.

![Moving a truck when the the trucks are in two groups.](wind_diagram_2.jpg)

If moving a launch-zone truck would cause the last truck to pass the safety truck, then you
must move the safety truck. Any balloon on a launch-zone truck should accompany that truck when it is moved.

### Moving the Safety Truck
To move the safety truck, you move slide it one column to the right.
If moving the safety truck would cause it to pass the lead truck, then you must move a
launch-zone truck.

![Moving a truck when the trucks are in a single group and the safety vehicle is not centered on the launch zone.](wind_diagram_3.jpg)

__Note:__ Any balloon cards that are in the launch zone (i.e. balloons that are in the unpacked or inflated states) should accompany the truck card on which they have been placed when that truck card is moved. 

### Advance a Balloon
Throughout the game, each balloon will progress through a series of states: packed, unpacked, inflated, and flying at altidues ranging from one to four. All balloons begin in the packed state.

On your turn, you should advance one balloon of your choice. If you cannot advance any of the balloons, then you should skip this step.

To advance a balloon, you should move it from its current state to the next. 
  - **Unpack:** To advance a balloon from the packed state to the unpacked state, place it horizontally on a launch-zone truck.
  - **Inflate:** To advance a balloon from the unpacked state to the inflated state, turn it so that it is placed vertically on its truck.
  - **Launch:** To advance a balloon from the inflated state to the flying state, move it to the bottom row of the game board above its truck. It will then be flying at an altitude of one.
  - **Ascend:**  To advance a balloon that is flying, move it up one row. It will then be flying at an altitude one more than before.
    - Balloons that are flying may never be orthogonally adjacent to one another.
    - The maximum altitude at which balloons can fly is four.


## Scoring
Use the scoring tokens to indicate the number of points scored by each balloon.
  - Place the scoring token numbered "1" on the leftmost balloon in the bottom row of the formation.
  - Scanning from left to right and bottom to top, place scoring tokens on the remaining balloons in the formation, placing the token with lowest remaining number on each balloon as you encounter it.

Your score is the sum of the scores for all of the balloons with which you are affiliated (i.e. that match your color card). The player with the highest score wins the game.

![Scores for each balloon at the end of a hypothetical game](scoring_diagram.jpg)

## Solo Mode
Aloft can also be played as a one-player game. This version of the game is similar to the multi-player version, differing in the following ways:
  - You will not use the color cards or the scoring tokens. You will only use two of the special shape balloon cards.
  - You will shuffle the balloon cards before dealing out the balloon cards in a single row below the game bard. If you choose to unpack a balloon on a given turn, you must unpack the first (leftmost) remaining balloon.
  - Balloons that are flying and that share a color may never be diagonally adjacent to one another.
  - Your score is equal to the number of adjacent columns required to contain the formation plus a three point penalty for every balloon which you failed to launch.