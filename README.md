# SquareSiege.io Game Development

This repository is for the development of SquareSiege.io, a dynamic, strategy-driven .io game. The game revolves around a simple yet engaging concept, taking place in a vast, open grid space where players navigate their squares and engage in strategic combat.

## Game Concept

SquareSiege.io places players in control of a single grid-sized square with a heart at its center. This heart represents the core of their fortress and the player's lifeline within the game. The game is designed to be intuitive, allowing players to move in any of the nine main directions at any given time.

## Fortress Building

The grid is populated with smaller squares that are a quarter of the size of a grid space. These squares materialize randomly, providing players with opportunities to attach them to their fortresses. As players continue to gather and attach these squares, they can gradually build larger and more formidable mobile fortresses. However, the size of the fortress impacts its mobility, adding a layer of strategic depth.

## Power-ups and Terrain

Adding more excitement to the gameplay, power-ups will spawn randomly across the map. These power-ups can provide temporary advantages such as speed boosts, brief invulnerability, increased square-launching speed, or a protective 'shield' square. The battlefield is not just a flat, open grid, but includes varied terrain that can impact strategy and movement.

## Gameplay Objectives

The primary goal in SquareSiege.io is twofold: protect your own heart square and attempt to destroy the heart squares of other players. Strategic combat comes into play when a square from a player's fortress comes into contact with another player's fortress square, resulting in the destruction of the squares at the point of contact.

Players can launch their fortress squares as projectiles in the direction they're moving. These can be used to attack other players or defend against incoming attacks. If a portion of a player's fortress becomes detached from the main structure, it will despawn after a few seconds, but there's a brief window where it can be reattached or claimed by another player.

## Scoring System

SquareSiege.io includes a scoring system based on the number of heart squares destroyed, squares collected, and enemies defeated. As players immerse themselves in the thrilling world of SquareSiege.io, they can aim to climb the leaderboard and demonstrate their strategic prowess.

## Game Philosophy

SquareSiege.io is a game of strategy, speed, and spatial awareness. The simplicity of its concept makes it easy for anyone to pick up and play, but its depth keeps players engaged. With every square gained or lost, players will experience the thrill of strategic combat in the fast-paced world of SquareSiege.io. 

This repository serves as the foundation for the development of SquareSiege.io, aiming to transform this exciting concept into a playable reality. All contributions towards achieving this goal are welcome.


# Tech Stack

## Frontend:

**React.js**: For building user interfaces.

## Middleware:

**Node.js & Express.js**: Node.js for running JavaScript on the server-side and Express.js for building the API.

## Backend:

**MySQL**: For the database.

## Package Management:

**NPM (Node Package Manager)**: For managing JavaScript packages that you'll use in your project, comes bundled with Node.js.

## Build Tools:

**Webpack & Babel**: Webpack for bundling your JavaScript files and Babel for compiling next-generation JavaScript into a backwards-compatible version.

## Hosting/Deployment:

**Heroku, AWS, Azure, or Google Cloud Platform**: For hosting your application. The choice depends on your specific needs and budget.

## Test Framework:

**Jest**: For testing your application.

## Real-Time Functionality:

**Socket.io**: For real-time bidirectional event-based communication.