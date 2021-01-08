# Rock Paper Scissors 
---
> Description : Rock paper scissors is a hand game usually played between two people, in which each player simultaneously forms one of three shapes with an outstretched hand. These shapes are "rock", "paper", and "scissors". This C++ Program [Mini Project] is aimed at automating one of the player called as Computerized Player and the taking rock, paper or scissor as an input from the used.
---

## Introduction

Rock paper scissors (also known by other orderings of the three items, with "rock" sometimes being called "stone", roshambo or ro-sham-bo) is a hand game usually played between two people, in which each player simultaneously forms one of three shapes with an outstretched hand. These shapes are "rock" (a closed fist), "paper" (a flat hand), and "scissors" (a fist with the index finger and middle finger extended, forming a V). "Scissors" is identical to the two-fingered V sign (also indicating "victory" or "peace") except that it is pointed horizontally instead of being held upright in the air.

A simultaneous, zero-sum game, it has only two possible outcomes: a draw, or a win for one player and a loss for the other. A player who decides to play rock will beat another player who has chosen scissors ("rock crushes scissors" or sometimes "blunts scissors"), but will lose to one who has played paper ("paper covers rock"); a play of paper will lose to a play of scissors ("scissors cuts paper"). If both players choose the same shape, the game is tied and is usually immediately replayed to break the tie.
[Read More on Wiki Pedia](https://en.wikipedia.org/wiki/Rock_paper_scissors)

## Game Play

The players may count aloud to three, or speak the name of the game (e.g. "Rock! Paper! Scissors!"), either raising one hand in a fist and swinging it down with each syllable or holding it behind their back. They then "throw" by extending it towards their opponent. Variations include a version where players throw immediately on the third count (thus throwing on the count of "Scissors!"), or a version where they shake their hands three times before "throwing". We are going to computerize this game play, so that computer will choose some random choice while the player will have the choice to choose one [Rock! Paper! or Scissors! ]

## Rules

A player who decides to play rock will beat another player who has chosen
scissors ("rock crushes scissors" or sometimes "blunts scissors"),
but will lose to one who has played paper ("paper covers rock");
a play of paper will lose to a play of scissors ("scissors cuts paper").
If both players choose the same shape, the game is tied and
is usually immediately replayed to break the tie.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/67/Rock-paper-scissors.svg/1200px-Rock-paper-scissors.svg.png" width = "600" height = "600"/>

Image Credits : Wiki Pedia


**Possible cases** -  

* if (player == rock) and (computer == paper); computer wins
* if (player == paper) and (computer == paper); tie
* if (player == scissors) and (computer == paper); player wins

* if (player == rock) and (computer == rock); tie
* if (player == paper) and (computer == rock); player wins
* if (player == scissors) and (computer == rock); computer wins

* if (player == rock) and (computer == scissors); player wins
* if (player == paper) and (computer == scissors); computer wins
* if (player == scissors) and (computer == scissors); tie





## Algorithm

1. The computer will choose a random choice between "Rock", "Paper" and "Scissor".
    Logic -
    = We will generate a random number between 1 - 100; if the number is in between
    = less than 33    --> Computer will choose Rock
    = 33 - 66         --> Computer will choose Paper
    = greater than 66 --> Computer will choose Scissor  

2. User Input will be taken.
3. Input will be compared with computers choice.
4. According to rules, one of them will win.


## Dependencies

* C++ Language

## Requirements

* 64 Bit Windows / Open Source Linux & its derivatives.
* Open Source Programming Tools like G++/GCC, C++ IDE (Visual Studio Code or any other).



## Output

<img src="https://github.com/shreyaschavhan/Rock-Paper-Scissors-Game/blob/main/Images/rock-paper-scissor.gif" width="1080" height="600" />

> A Project by [Shreyas Chavhan](https://github.com/shreyaschavhan)
