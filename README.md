# Nightfall

## Description

- Web-based 2D platformer Metroidvania game using Phaser and themed to nightlife.
- [GitHub Repository](https://github.com/phopps/nightfall)

## Table of Contents

- [Nightfall](#nightfall)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Technologies](#technologies)
  - [Gameplay](#gameplay)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Badges](#badges)
  - [License](#license)
  - [Contributions](#contributions)
  - [Testing](#testing)
  - [Credits](#credits)
  - [Inspiration](#inspiration)
  - [Notes](#notes)
  - [Metroidvania Game Jam Rules](#metroidvania-game-jam-rules)
  - [Todo](#todo)

## Technologies

- [Phaser](http://phaser.io/)
- [Phaser GitHub](https://github.com/photonstorm/phaser)
- TypeScript

## Gameplay

- User starts program
- Load Intro Screen
  - Splash screen video for introduction to game
- Load Main Menu
  - New Game: Create a new game save file and start a new run.
  - Load Game: Load a game save file and continue saved run.
  - Save Game: Save your current run to a game save file.
  - Lore: Read descriptions of game lore and terminology.
  - Settings: Adjust audio, graphics, and gameplay settings.
  - Exit: Quit the entire program.
- New Game
  - Prompt user to input `username`

<!-- TODO: New/Load/Save Game, Lore, Settings, Exit descriptions and functionality -->

## Features

<!-- The game takes place over a series of ‘runs’, one run represents hacking through a single ‘layer’ of a simulation of reality.

Turn based combat is cooldown-based, with no required secondary resource except for major powers.

Upgrades are handled via Hardware and Software. Abilities (mostly active, some passive) are handled by software, and Hardware modifies core stats, and has passives that dramatically change other behaviors. -->

<!-- TODO: Why build it? What problems does it solve? What has been learned while working on it? -->

## Installation

Install all Nightfall packages by running `npm install` or `npm i`.

## Usage

Start Nightfall by running `npm start`.

- Players start a new ‘run’ by picking their character class, and then choosing the first ‘server’ to hack into.
- Each server provides randomized rewards, as well as clues that enable the player to finish each ‘act’.
- If the player is able to successfully complete all 3 acts, they win that run, but only by unlocking and completing the 4th act will the player be able to move to the next ‘layer’.
- Progression takes the form of ‘unlocks’, which are diegetic knowledge about how to find and utilize other pieces of hardware and software, giving players more strategic choices.

Restart Nightfall by running `npm restart`.

Stop Nightfall by running `npm stop`.

Start the Nightfall` development environment by running `npm run develop`.

## Badges

<!-- TODO: Add badges displaying repository information -->

## License

MIT

## Contributions

<!-- TODO: How to contribute? -->

## Testing

- The Jest testing framework is used alongside the concept of test-driven development.
- Install Jest by running `npm install jest --save-dev` or `npm i jest -D`.
- Once Jest is installed, open the `package.json` file, go the the `scripts` property, and update the value of the `"test"` property to `jest`.
- Running `npm test` will run all tests in the `__test__` folder, or `npm test <filename>` can be used to specify a specific test to run by replacing `<filename>` with the name of the test file.
- Test suite files use the `<filename>.test.js` naming convention by replacing `<filename>` with the name of the file being tested.

## Credits

<!-- TODO: Link profile urls -->

- Patrick Hopps
- Jaquel Rey

## Inspiration

- [K-438B](https://github.com/huhmiel-games/K-438B)
  - [K438-B_DEMO](https://blunt76.itch.io/k438-b-beta)
- [PhaserEditor2D-v3](https://github.com/PhaserEditor2D/PhaserEditor2D-v3)
- [PhaserEditor_Tutorial_Platformer_1](https://github.com/PhaserEditor2D/PhaserEditor_Tutorial_Platformer_1)
- [Phaser 3 Webpack Project Template](https://github.com/photonstorm/phaser3-project-template)
- [Phaser 3 Typescript Webpack Boilerplate](https://github.com/troyedwardsjr/phaser3-typescript-webpack)
- [Phaser 3 API Documentation](https://github.com/photonstorm/phaser3-docs)
- [Phaser 3 Examples](https://github.com/photonstorm/phaser3-examples)
  - [matter platformer with wall jumping.js](https://labs.phaser.io/view.html?src=src/tilemap/collision/matter%20platformer%20with%20wall%20jumping.js&v=3.60.0-beta.14)
  - [another link to same as above](https://labs.phaser.io/edit.html?src=src/tilemap/collision/matter%20platformer%20with%20wall%20jumping.js)
  - [matter platformer modify map.js](https://labs.phaser.io/view.html?src=src/tilemap/collision/matter%20platformer%20with%20wall%20jumping.js)
  - [Phaser - tilemap/collision](https://labs.phaser.io/index.html?dir=tilemap/collision/&q=)

## Notes

- Install Phaser via npm using `npm install phaser`
- Phaser is on jsDelivr which is a "super-fast CDN for developers"
  - Include the following in your html: `<script src="//cdn.jsdelivr.net/npm/phaser@3.51.0/dist/phaser.js"></script>`
  - or the minified version: `<script src="//cdn.jsdelivr.net/npm/phaser@3.51.0/dist/phaser.min.js"></script>`

## Metroidvania Game Jam Rules

- Rules
  1. Assets should all be made during the jam period. General purpose code, designing, bases and models, placeholders, and story can be made before the start of the jam. Here's clarification.
  2. External assets can be used if you have the rights to and leave credit to the author when submitting in the "External assets" field when required. Of course, the assets you choose don't have to be made during the jam.
  3. Incomplete games are accepted, I would like to see them evolve if it's a project that you'll continue. So don't stress to make a complete game! But your submission should be playable.
  4. Teaming is accepted and there is no maximum team members.
  5. You are free to use any engine you want.
  6. The game needs to have a PG-13 rating or below. To be clear: no nudity, excessive swearing, no gore (for the subtilities of that one, refer yourself to these two posts: Post 1 and Post 2)
  7. Your game should be free! You understand that selling it will cut out your ratings. You can put it on a sale for the duration of the rating period and set it back to its normal price after that.
  8. I'm accepting late entries until 24 hours after the end of the submission period. In order to submit late, first publish your game to itch, and then send me the link, either on Discord or in the Community tab. Uploads will also be unlocked, so if you have a bug fix to publish, do it during this time!
- Optional theme: Nightlife
  - It is voted on one week before the jam, and the theme is announced at the start of the jam.
  - You are free to use the theme or not, it is only for inspiration and won't affect your score.
- Rating criteria
  1. Enjoyment: How did you like the game?
  2. Design:  Includes a lot of things, like balance, level design, gameplay experience, creativity, etc. How was that?
  3. Presentation: Was the game delivered in a good way? How was the consistent aesthetic?
  4. Metroidvania: Does this game belong in this jam? Was the Metroidvania subtle or could you clearly say it was a Metroidvania?
- Prizes
  - Top 2:  $20~ Steam item
  - Top 10:  Raffled giveaways & free/discounted courses (the first few courses will be in development  after the jam)
  - Prizes will be rewarded to top jam contestants by LearnIndie.com
  - Join course.learnindie.com to be eligible for prizes!

## Todo

- [ ] [Phaser - HTML5 Game Framework (Create Your First Phaser 3 Example)](https://newdocs.phaser.io/docs/3.55.2)
- [ ] [Getting Started with Phaser 3](https://phaser.io/tutorials/getting-started-phaser3/index)
- [ ] [Making your first Phaser 3 game](https://phaser.io/tutorials/making-your-first-phaser-3-game/part1)
- [ ] Create MVP for game jam
  - [ ] GitHub issues, branches, collaborators
