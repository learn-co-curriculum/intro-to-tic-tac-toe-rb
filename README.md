# Intro To Tic Tac Toe in Ruby

## Objectives

1. Learn about building Tic Tac Toe in Ruby.

## Introduction

We're going to be learning how to build [Tic Tac Toe](https://en.wikipedia.org/wiki/Tic-tac-toe) in Ruby. If you're unfamiliar with the game, it is played on a 3 by 3 grid of available cells. The goal of the game is to get three of your tokens, X or O, in a row, including diagonals.

The following example game is won by the first player, X:

![X Wins](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Tic-tac-toe-game-1.svg/958px-Tic-tac-toe-game-1.svg.png)

## Why build Tic Tac Toe?

I'm sure you're really excited about building the next Facebook or Instagram, but like most things in life, we have to crawl before we walk, and walk before we run, and build Tic Tac Toe before we build large and complex applications.

Tic Tac Toe is a simple ruleset that flexes the basic concepts in programming, like data structures for storing the board, conditional logic for knowing whose turn it is or if someone has won.

Because of the simple game rules, Tic Tac Toe is very easy to decompose into discrete, small, functionality, that we can then put together to create a complete game. This process of decomposition and synthesis, breaking something down and putting it back together, is absolutely essential to programming.

The simple interface Tic Tac Toe requires, a basic 3 x 3 grid, is also easy to port to multiple interfaces. We can build a command line version of Tic Tac Toe or a web-based version. We can even build a SMS version of Tic Tac Toe if we wanted.

![Web Tic Tac Toe](https://dl.dropboxusercontent.com/s/q3yyuquszgh5g4y/2015-09-29%20at%2010.45%20AM.png)

![CLI Tic Tac Toe](https://dl.dropboxusercontent.com/s/71iskdi76syyqhb/2015-09-29%20at%2010.46%20AM.png)

Beyond being able to move easily between interfaces, we can also move between programming styles, building Tic Tac Toe in a procedural or functional style first, then moving that to an Object Oriented version, and finally, adding our Tic Tac Toe model to a Sinatra Web Application.

Once you've built your basic 2-player version of Tic Tac Toe, you are free to extend it by creating a 1 player version and trying to program an unbeatable AI.

<iframe width="753" height="380" src="https://www.youtube.com/embed/F7qOV8xonfY?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

## Pseudo-Code for Tic Tac Toe

The general procedure for Tic Tac Toe is as follows:

1. Create a structure to store and represent the state of the board.
2. Welcome the players.
3. Get the user's move in the form of some input.
4. Make sure their move is valid.
5. Check to see if the game has been won or came to a draw.
6. Change the player turn and let the next player make a move.
7. Repeat until the game is over.

As your progress through this course, we'll break all these requirements down into simple, cumulative labs throughout the track. You'll be surprised at how quickly you'll learn to do something this complex.

Let's get started learning enough Ruby to build Tic Tac Toe.
