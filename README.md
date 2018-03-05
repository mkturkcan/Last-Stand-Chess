# Last Stand Chess: Implementation and AI

## Introduction

Last Stand is designed to be used for tactics problems and for battles in large wargames or RPGs.

## Rules

Last Stand is a Chess variant with the following rule changes:
* The King is replaced by a second Queen. 
* Players make three consecutive moves per turn instead of one.
* If the winner is less than 9 points ahead at the time of the victory, the game is declared a draw.

Last Stand also implements some non-traditional pieces, like impassable mountains. 

## Playing Last Stand Chess:

This repository contains a modification of the [Sunfish](https://github.com/thomasahle/sunfish) AI for Last Stand chess. The AI currently does not take the three-move rule into consideration.

By default the game is currently configured to be AI vs AI, with the black team's player periodically receiving reinforcements on a randomly generated battlefield.