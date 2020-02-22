# Phaser 3 + TypeScript Starter Kit

This repository contains all the code necessary to start making a game in Phaser 3 using TypeScript. It is a fork of [this repo](https://github.com/josephmbustamante/phaser3-typescript-starter-kit) and all credit should go to [Joe Bustamante](https://github.com/josephmbustamante). This is just my current prefered basic setup for phaser3 with TypeScript.

## Changes

- Added eslint and my prefered rules.
- Added some stricter type rules in tsconfig
- Added a .prettierrc
- Fixed the warnings and errors caused by my new rules

## How to Use

You should be able to clone this repository and run `yarn install` to get any of the necessary dependencies.
Once you're done installing, simply run `yarn dev` and the game should begin to run. You'll have to open an internet browser and go to the port that the game is running on (usually `localhost:8080` by default).

The game opens up to a main menu. Only the "Start Game" button does anything - the other two are placeholders. If you click "Start Game", you'll be taken to a black screen with a small sprite. You can move the sprite with the arrow keys. This starter kit is far from feature complete, but it's meant to take away the boilerplate that can come with getting a Phaser 3 + TypeScript project up-and-running.
