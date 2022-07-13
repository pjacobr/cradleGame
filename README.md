# cradleGame
Games themed after Cradle Book Series by Will Wight

## Requirements:
This will include several games:
1. Mortal Combat style 1 v 1 game
   1. Each player chooses their character
   2. Gameplay begins until 1 player runs out of health/lives
2. Maze Solver game 2 player collaboration game
   1. Choose your character
   2. Choose character #2
   3. Move through 5 mazes that require help from 2nd player to solve
3. Social chat room
   1. Enter your name
   2. Choose your character
   3. Walk around and chat with people

- Linter
- Tests
- CI/CD
- Pre commit hooks
- Cloud Deployed
- Type hinting
- Modular code
- Multiplayer over the network
- file structure

## Server
The server will take the role of managing open sockets and providing real time data for the 
various clients that are connected.

## Client
The client will be the user interface for the game. It will connect with the server and maitain an 
open socket.
