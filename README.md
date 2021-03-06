# batch5-pacman
[![CircleCI](https://circleci.com/gh/pesto-students/batch5-pacman.svg?style=svg)](https://circleci.com/gh/pesto-students/batch5-pacman)

### Overview:

Multiplayer PacMan game which is very similar to the classic pacman game, along with the option to play with a random player.

### Goals:

Build the Multiplayer PacMan game which would work smoothly with various fun features and should be user engaging.

### Gameplay Logic:
 - Pacman should move in four directions. 
 - There are four Ghosts in total.
 - Ghosts are initially in the “monster pen”  which is at the center of the maze, emerging from it.
 - On every intersection, ghost direction is computed pseudorandomly.
 - There are 244 dots in the maze, 240 normal dots with ten points each and four energizers with 50 points each.
 - When the PacMan consumes the ghosts, 200 points are added.
 - Bonus Symbols (fruits) - Four in total.


### Features:
 - Player Modes : Single Player and Multiplayer
 - Authentication
 - Difficulty Levels
 - Leaderboard

### Ghost Modes:
- Chase Mode
- Scatter Mode
- Frightened Mode


### Tech Stack: 

- Project management: GitHub Projects
- Game Rendering: Canvas
- Deployment: AWS (Backend), Netlify(Frontend)
- Authentication: Token based (JWT) / Passport.js
- Database: Mongodb (mlab)
- CI/CD: CircleCI

### URLS: 

- Game-staging: https://mc-pacman.netlify.com/
- Server URL: https://pacman.us-east-2.elasticbeanstalk.com/
