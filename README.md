### Lucky Roller
This repository houses "Lucky Roller", an interactive two-player dice game. This project is part of "The Complete JavaScript Course 2024: From Zero to Expert!" taught by Jonas Schmedtmann on Udemy. The game is designed to teach DOM manipulation, event handling, and fundamental game development using JavaScript.
## Table of Contents
Introduction
Technologies Used
Setup
Game Rules
Features
Credits
# Introduction
Lucky Roller is a web-based dice game where players take turns rolling a dice to accumulate points with the goal of reaching or surpassing a score of 100. Players can roll multiple times per turn, but risk losing all temporary gains if they roll a 1. The game showcases dynamic interactions with the DOM and responsive design.
# Technologies Used
HTML
CSS
JavaScript
# Setup
To get this game up and running on your local machine, follow these steps:
git clone https://github.com/marvenilla/lucky-roller.git
cd lucky-roller
open index.html
# Game Rules
Two players take turns in this round-based game.
On each turn, a player rolls the dice as many times as they choose, each result adding to their round score.
If the player rolls a 1, they lose their round score and it's the next player's turn.
Players can opt to 'Hold', which adds their round score to their global score, then it becomes the other player's turn.
The first player to reach 100 points on their global score wins the game.
# Features
Animated dice roll effect showing real-time dice outcomes.
Real-time score updates for both current and total scores.
Persistent game state across turns, allowing for seamless gameplay until a player wins or resets the game.
Responsive design ensuring playability on both desktop and mobile devices.
# Credits
Jonas Schmedtmann for creating the course that this project is based on.
All resources for this game were provided through "The Complete JavaScript Course 2024: From Zero to Expert!" by Jonas Schmedtmann on Udemy.
