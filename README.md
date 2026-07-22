# Physics Flipper project

Project developed for the class **[Tools Programming](#tools-programming)** and **[Physics Programming](#physics-programming)** of the *Master in Computer Game Development* of the *University of Verona (Italy)*

## Setup

This project uses Git submodules and Git LFS.

​```bash
git clone --recurse-submodules <repo-url>
​```

If already cloned without the flag:
​```bash
git submodule update --init --recursive
git lfs pull
​```

### Requirements
- Unreal Engine 5.7

### How to run
1. Open `PhysicsFlipper.uproject`
2. Press Play
3. Enjoy :)

## Project

The goal of the project was to develop a Pinball that uses the physics of the Unreal Engine

### Mode 1: Player mode

The player can apply an impulse to both of the paddle ([command](#command))

### Mode 2: AI mode

The (basic) AI apply by itself the impulse and is able to play alone.

### Command

General command:
- P: Pause the game
- M: Return to the Menu

Player mode command:
- Left mouse click, left arrow, A: Apply an impulse to the left paddle
- Right mouse click, right arrow, D: Apply an impulse to the right paddle 


## Tools Programming

The test was to use correctly Git and the plugin [UEGitPlugin](https://gitlab.com/mastergamedev-vr/uegitplugin) (fork of [UEGitPlugin](https://github.com/ProjectBorealis/UEGitPlugin))

The development follows the **git-flow** branching model: work was split into multiple feature branches (`ball`, `paddle`, `bouncers`, `camera`, `board`, `UI`, `AI`, `sound`, ...), each merged into `develop` and finally into `main`.

## Physics Programming

The test was to develop the game using entirely the engine's physics, without animation.


## Techincal Stack
- **Engine**: Unreal Engine 5.7
- **Programming**: Blueprint
- **Audio**: Built-in Unreal Engine System

## Audio licence

All the audio are from [Freesound](https://freesound.org/), with [Creative Commons licence (CC)](https://creativecommons.org/2008/04/22/attribution-only-as-default-policy-otago-polytechnic-on-the-how-and-why-of-cc-by/):
- "Launcher sound" by [BeroundSound](https://freesound.org/people/BeroundSound/)
- "Bounce basic sound" by [quatricise](https://freesound.org/people/quatricise/)
- "Bounce point sound" by [cabled_mess](https://freesound.org/people/cabled_mess/)
- "Lose point sound" by [suntemple](https://freesound.org/people/suntemple/)
- "Paddle sound" by [Squirrel_404](https://freesound.org/people/Squirrel_404/)