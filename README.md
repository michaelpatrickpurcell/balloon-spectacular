# Aloft
A lightweight strategy game about hot-air ballooning that can be played either competitively or cooperatively. During the game you will oversee a mass ascension at a balloon festival and try to ensure that your balloons end up in the best positions for the official publicity photo that will be taken of the event.

## Overview
Aloft is a game for one to five players. It can be played in approximately thirty minutes and is intended for players who are at least eight years old.

During the game, you will launch a flight of hot-air balloons. You can play either cooperatively or competitively. In a cooperative game, you will work together to launch all of the balloons in as tight a formation as possible. In a competitive game, each player will be affiliated with a different colour and you will try to ensure that the balloons of your colour are both higher and closer to the front of the formation than the balloons of your opponents' colours.

## Components
  - 13 balloon cards
     - 10 regular balloon cards
     - 3 special shape cards
  - 5 truck cards
  - 5 colour cards
  - 1 game board

The number of cards of each type that you will use in your game depends on the how many people are playing. See the table below for details. Notice that you will always use all of the regular balloon cards but, unless you are playing a five-player game, you will not use all of the special shape cards, truck cards, or colour cards.

| Player Count | 1 | 2 | 3 | 4| 5 |
| ----------: | ---: | ---: | ---: | ---: | ---: |
| Regular Balloon Cards | 10 | 10 | 10 | 10 | 10
| Special Shape Cards | 2 | 0 | 1 | 2 | 3 |
| Truck Cards | 4 | 4 | 4 | 4 | 5 |
| Colour Cards | 0 | 2 | 3| 4| 5| 


## Set Up
  1. If you are playing a competitive game, deal one colour card at random to each player. Your colour card will determine the colour of balloons with which you are _affiliated_. Do not reveal this card to the other players until the end of the game. If you are playing a cooperative game, then you should skip this step.
     - Each regular balloon card is affiliated with two of the five possible colours.  The colours that a balloon card is affiliated with are the colours of the envelope of the balloon depicted on that card. Special shape cards are not affiliated with any colour. 
  2.  Place the truck cards in a single row below the right-hand side of the game board. These cards will comprise the _launch zone_.
  3.  Collect the regular balloon cards and special shape cards that you will use during your game (see Components above for details). These cards will comprise the _balloon deck_.
  4.  If you are playing a cooperative game, shuffle the balloon deck. If you are playing a competitive game, then you should skip this step. 
  5.  Place the balloon deck below the launch zone. The balloon deck should be face up and centered on the launch zone.

![Set up for a four-player game.](set_up_diagram.jpg)

## Gameplay
On your turn, two things will happen:
  1. You will advance one balloon.
  2. If any balloons are flying, the wind blows.

The game ends when all of the balloons are flying or when the all of the truck cards have moved past the leftmost column of the play area.

### Advance a Balloon
Throughout the game, each balloon will progress through a series of states: packed, unpacked, inflated, and flying at various altitudes. On your turn, you can advance any one balloon of your choice. If you cannot advance any of the balloons, then you should skip this step.

To advance a balloon, you move a balloon from its current state to the next. 
  - All balloons begin in the packed state. All balloons in the packed state should be in the balloon deck.
  - To advance a balloon from the packed state to the unpacked state, you should remove it from the balloon deck and place it horizontally on one of the truck cards.
     - In a cooperative game, you may only advance the first balloon (top card) in the balloon deck.
     - In a competitive game, you may advance any balloon in the balloon deck.
- To advance a balloon from the unpacked state to the inflated state, you should turn it so that it placed vertically on its truck card.
- To advance a balloon from the inflated state to the flying state, you should slide it into the bottom row of the play area directly above its truck card. It will then be flying at an altitude of one.
   - Balloons that are flying (at any altitude) may never be orthogonally adjacent to another balloon which is flying.
   - In a cooperative game, balloons that are flying may never be diagonally adjacent to another balloon which is flying and with which it shares a colour. 
- To advance a ballon that is flying, you should slide it up one row so that its altitude increases by one.
   - The maximum altitude at which balloons can fly is four.
   - Balloons never descend (decrease their altitude) or move horizontally. 

### The Wind Blows
If any balloons are flying, then after you advance a balloon the wind will blow. The wind always blows from the left to right over the launch zone and it changes the position of balloons that are flying relative to the launch zone. Rather than move the balloons which are flying, however, you will move the launch zone from right to left (in the opposite direction of the wind) to model this effect.

When the wind blows, you will do one of the following:
  - If the truck cards are in adjacent columns and the balloon deck is centered on the launch zone (e.g. the starting position), or if there are no cards remaining in the balloon deck, then you should move the leftmost truck one column to the left.

  ![The wind blows when the trucks are in a single group and the baloon deck is centered on the launch zone.](wind_diagram_1.jpg)

  - If the truck cards are not in adjacent columns, then the truck cards will be in two groups which are separated by one empty column. You should slide the leftmost truck from the second group one column to the left. It should then be the rightmost truck in the first group.

  ![The wind blows when the trucks are in two groups.](wind_diagram_2.jpg)

  - If all of the truck cards are in adjacent rows, but the balloon deck is not centered on the launch zone (e.g. after each of the truck cards has been moved one time), then you should slide the balloon deck one position to the left so that it is centered on the launch zone.

  ![The wind blows when the trucks are in a single group and the baloon deck is not centered on the launch zone.](wind_diagram_3.jpg)

__Note:__ Any balloon cards that have been placed on a truck card (i.e. that are in the unpacked or inflated states) that moves when the wind blows should be moved as well. 

## Scoring
After the game ends, you should compute your score.

### Cooperative Game
In a cooperative game, your score is number of adjacent columns required to contain the formation (i.e. the width of the formation) when all of the balloons are flying. If you were unable to launch all of the balloons during the game, your score is equal to the width of the formation plus the number of balloons that you were unable to launch. Your objective is to minimize your score.

### Competitive Game
In a competitive game, each balloon scores a number of points that is determined by its position within the formation. In general, balloons that are flying at higher altitudes score more points than those that are flying at lower alititudes.  If balloons are flying at the same altitude, then the balloons that are closer to the front (right-hand side) of the formation score more points than the balloons that are closer to the back (left-hand side) of the formation. 

More precisely, each balloon scores a number of points equal to one plus the number of balloons flying at a lower altitude than itself plus the number of balloons flying at the same altitude as itself but behind it (to the left) in the formation.

For example, the leftmost balloon in the bottom row of the formation always scores one point while the rightmost balloon in the top row of the formation scores one point for every balloon that is flying at the end of the game.  

Your score is the sum of the scores for all of the balloons with which you are affiliated. You should reveal your colour card when you announce your score so that everyone can verify that the required computations have been performed correctly. The player with the highest score wins.

