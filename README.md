Dice Driven Journey: Adventures on Dice Islands 🎲🌍
Welcome to Dice Driven Journey, an innovative multiplayer mobile game blending luck, strategy, and social interaction. Players roll dice to unlock rewards, build and upgrade villages, and compete with friends in a dynamic and engaging universe.

Table of Contents
Introduction

Features

Game Mechanics

Architecture

Installation

Technologies Used

Future Enhancements

Contributors

Introduction


Dice Driven Journey was designed to provide a unique gaming experience. Inspired by popular games like Coin Master and Dice Dreams, it enhances these concepts by reducing dependency on microtransactions, enriching features, and implementing a fair progression system.

Features


Dice Rolling Mechanics: Unlock rewards such as coins, shields, and chests.

Village Building:

Build and upgrade villages to unlock new levels.

Each village includes a Village Manager and Village Builder for smooth upgrades and transitions.

Special Events:

Slot Machine: Spin for a chance to win high-value items.

Pet Event: Feed and upgrade pets to earn exclusive rewards.

Trail Event: Traverse paths to unlock hidden treasures.

Spinning Wheel Event: Spin the wheel to win additional rewards like coins, shields, or extra dice.

Social Play:

Connect with friends via Facebook.

Compete on leaderboards and engage in friendly attacks.

Reward System:

Daily rewards to encourage consistent gameplay.

Mystery cards offering surprise gifts like coins or dice.

Game Mechanics


Dice Rolling:

Dice outcomes determine rewards such as coins, shields, or attacks.

Players progress by rolling dice to unlock actions and rewards.

Village Building:

Start with a basic village and upgrade buildings using collected resources.

Unlock 7 unique villages with themed designs.

Transition smoothly between villages with the Level Selection Manager.

Special Events:

Slot Machine, Pet Event, Trail Event, and Spinning Wheel.

Each event is managed by a specific Event Manager.

Reward System:

Players earn rewards through consistent gameplay and special events.

Architecture

Physical Architecture

Client: Players interact with the game through mobile devices, sending API requests for game actions.

Backend:

Node.js serves as the server, handling player data, game logic, and API endpoints.

MongoDB stores player data, village configurations, and game states.

Facebook SDK: Enables seamless social interactions and leaderboard integration.

Logical Architecture

Managers:

Game Manager: Handles overall game logic and state.

Sound Manager: Controls in-game audio.

Village Manager: Oversees village upgrades and transitions.

Level Selection Manager: Manages progression between villages.

Event Managers: Each event has its dedicated manager for handling interactions and animations.

Installation
Clone the repository:

git clone <repository-link>

Since the project exceeds GitHub's size limits, the full Unity client can be accessed on GitLab: GitLab Repository

Install dependencies for the backend:

npm install

Open the Unity project and configure the environment.

Technologies Used

Game Engine: Unity engine

Backend: Node.js

Database: MongoDB

Social Integration: Facebook SDK

Version Control: Git

Tools: Postman, Unity Profiler, Visual Studio

Future Enhancements

Expanding the number of villages beyond 7.

Adding more special events and mini-games.

Implementing cross-platform gameplay for Android and iOS.

Enhancing performance optimization for low-end devices.

Contributors

Mohamed Amine Koubaa – Lead Developer


This repository is a mirror of the original project hosted on GitLab:
[GitLab Repository](https://gitlab.com/needaimdark/dice_driven_unity_client)
