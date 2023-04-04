# Aloft
An 18-card game designed by Michael Purcell.

## Overview
Aloft is a game for one to five players. It can be played in approximately thirty minutes and is intended for players who are at least eight years old.

During the game, you will launch a flight of hot air balloons. You can play either cooperatively or competitively. In a cooperative game, you will work together to launch all of the balloons in as tight a formation as possible. In a competitive game, each player will be affiliated with one colour and you will try to ensure that the balloons of your colour are as close to the front of the formation as possible.

## Components
  - 13 balloon cards
     - 10 regular balloon cards
     - 3 special shape cards
  - 5 truck cards

The number of cards of each type that you will use in your game depends on the how many people are playing. See thte table below for details. Notice that you will always use all of the regular balloon cards but, unless you are playing a five-player game, you will not use all of the special shape cards or truck cards.

| Player Count | 1 | 2 | 3 | 4| 5 |
| ----------: | ---: | ---: | ---: | ---: | ---: |
| Regular Balloon Cards | 10 | 10 | 10 | 10 | 10
| Special Shape Cards | 2 | 0 | 1 | 2 | 3 |
| Truck Cards | 4 | 4 | 4 | 4 | 5 |


## Set Up
  1. If you are playing a competitive game, deal one truck card at random to each player. The colour of your truck card will determine which colour of balloons that you are affiliated with. If you are playing a cooperative game, then you should skip this step.
  2.  Place the truck cards in a single row below the right-hand side of the play area. These cards will comprise the _launch zone_.
  3.  Collect the regular balloon cards and special shape cards that you will use during your game (see Components above for details). These cards will comprise the _balloon deck_.
  4.  If you are playing a cooperative game, shuffle the balloon deck. If you are playing a competitive game, then you should skip this step. 
  5.  Place the balloon deck below the launch zone. The balloon deck should be face up and centered on the launch zone.
  6. Clear the play are above and to the left of the launch zone.
     - Ensure that there is enough space for four rows of cards.
     - Ensure that there is enough space for twelve columns of cards.  

![Set up for a four-player game.](set_up_diagram.jpg)

## Gameplay
On your turn, two things will happen:
  1. You will advance one balloon.
  2. If any balloons are flying, the wind blows.

The game ends when all of the balloons are flying or when then wind blows the balloons past the end of the play area. 

### Advance a Balloon
Throughout the game, each balloon will progress through a series of states: packed, unpacked, inflated, and flying at various altitudes. On your turn, you can advance any one balloon of your choice. If you cannot advance any of the balloons, then you should skip this step.

To advance a balloon, you move a balloon from its current state to the next. 
  - All balloons begin in the packed state. All balloons in the packed state should be in the balloon deck.
  - To advance a balloon from the packed state to the unpacked state, you should remove it from the balloon deck and place it horizontally on one of the truck cards.
     - In a cooperative game, you may only advance the first balloon (top card) in the balloon deck.
     - In a competitive game, you may advance any balloon in the balloon deck.
- To advance a balloon from the unpacked state to the inflated state, you should turn so that it placed vertically on its truck card.
- To advance a balloon from the inflated state to the flying state, you should slide it up one position so that it has an altitude of one.
   - Balloons that are flying (at any altitude) may never be orthogonally adjacent to another balloon which is flying.
   - In a cooperative game, no balloon may be diagonally adjacent to any balloon which is flying and with which is shares a colour. 
- To advance a ballon that is flying, you should slide it up one position so that its altitude increases by one.
   - The maximum altitude at which balloons can fly is four.
   - Balloons never descend (decrease their altitude) or move horizontally. 

### The Wind Blows
If any balloons are flying, then after you advance a balloon the wind will blow. The wind always blows from the left to right over the launch zone and it changes the position of balloons that are flying relative to the launch zone. Rather than move the balloons which are flying, however, you will move the launch zone in the opposite direction of the wind (from right to left) to model this effect.


To apply the wind, you will do one of the following:
  - If the truck cards are in adjacent columns and the balloon deck is centered on the launch zone (e.g. the starting position), then you should move the leftmost truck one column to the left.

  ![The wind blows when the trucks are in a single group and the baloon deck is centered on the launch zone.](wind_diagram_1.jpg)

  - If the truck cards are not in adjacent columns, then the truck cards will be in two groups which are separated by one empty column. You should slide the leftmost truck from the second group one column to the left. It should then be the rightmost truck in the first group.

  ![The wind blows when the trucks are in two groups.](wind_diagram_2.jpg)

  - If all of the truck cards are in adjacent rows, but the balloon deck is not centered on the launch zone (e.g. after each of the truck cards has been moved one time), then you should slide the balloon deck one position to the left so that it is centered on the launch zone.

  ![The wind blows when the trucks are in a single group and the baloon deck is not centered on the launch zone.](wind_diagram_3.jpg)


## Scoring
After the game ends, you should compute your score.

In a cooperative game, your score is number of adjacent columns required to contain the formation (i.e. the width of the formation) when all of the balloons are flying. If you were unable to launch all of the balloons during the game, your score is equal to the width of the formation plus the number of balloons that you were unable to launch. Your objective is to score as few points as possible.

In a competitive game, each balloon scores a number of points equal to the number of the column that it is in. The columns should be numbered from one to twelve with column one on the left-hand side of the play area and column twelve on the right. Your score is the sum of the scores for all of the balloons of your colour. The player with the highest score wins.

