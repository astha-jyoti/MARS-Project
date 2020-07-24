# Martians' TicTacToe
Microsoft Engage 2020

## Abstract

The aim of this project is to contribute in MARS COLONIZATION PROGRAM by making a web-based application of TIC TAC TOE game using Minimax algorithm.

## Motivation

In today’s digital world, the dawn of new technologies has provided an upsurge to countless AI driven resolutions. So a world without AI is almost impossible. Hence this program helps us learn about AI concepts and its foundations. It also helps us learn about various problem solving agents and also on how to solve problems by searching, especially beyond the Classical search.

## Architecture

![Flow Chart](https://github.com/suja-g/MARS-Project/blob/master/Images/Flowchart.png)

1. **Offline Mode :** Here two users can play against each other in same system
2. **Online Mode :** Here two users can play against each other remotely. Two options are provided under online mode - Create game and Join game. When we select create game a unique room id is created which we can share with our friends. When we select join we are asked to enter Room Id. If a room already has two users inside, another person cannot join the game and a prompt message gets displayed. By default, game creater takes 'X' sign and the other user takes 'O' sign.
3. **Bot Mode :** Here we get to play agains the computer. We are given chance to select between three levels of hardness and also we can select our sign. 'X' sign gets to play first.

### Algorithms and Packages
1. We used minimax algorithm for Human vs Ai game
2. We used PubNub for remote connection to create game lobby channel.

## Team Members
1. [Astha Jyoti](https://github.com/astha-jyoti)
2. [Divya Singhal]
3. [Namratha Thadi]
4. [Suja G](https://github.com/suja-g)

## Reference
[Basics of PubNub in javascript](https://www.pubnub.com/docs/platform/quickstarts/javascript)

To play our game [Click Here](https://astha-jyoti.github.io/MARS-Project/)
