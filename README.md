# LIDAR

A short atmospheric horror experience built in Unity, where sight is replaced by sound and scanning.

## Overview

LIDAR is an experimental first-person exploration game set on a dead world where all light has vanished. The player is sent to investigate an abandoned research site, documenting key locations using a LIDAR scanning device.

Instead of traditional rendering, the environment is revealed through bursts of projected points — forcing the player to interpret shape, distance, and movement in darkness.

## Core Concept

- The sun is gone. There is no light.
- The only way to perceive the world is through a **LIDAR scanner**.
- The player must:
  - Scan environments using a sweeping dot projection system
  - Identify key locations
  - Record observations manually in a notebook

## Features

### LIDAR Vision System
- Emits a grid-based scan of the environment
- Points fade over time
- Scan is captured at the moment of firing (independent of camera movement)
- Encourages spatial reasoning and memory

### Notebook System
- Fully interactive, player-drawn notebook
- Supports:
  - Freehand drawing
  - Erasing
  - Persistent notes
- Used to document findings and progress objectives

### Dynamic Documentation
- Key locations must be **observed and recorded manually**
- Writing near points of interest completes objectives
- System-generated notes can overwrite player entries, forcing reinterpretation

### Environmental Interaction
- Objects can respond to scanning and proximity
- Areas are "completed" through player observation and documentation

## Gameplay Loop

1. Enter a new area
2. Scan surroundings using LIDAR
3. Interpret shapes and structures
4. Record findings in the notebook
5. Progress by identifying key locations
6. Adapt as information becomes unreliable or overwritten

## Themes

- Isolation  
- Unreliable perception  
- Loss of control  
- Observation vs reality  

## Controls

| Action        | Input        |
|--------------|-------------|
| Move          | WASD        |
| Look          | Mouse       |
| Scan (LIDAR)  | Left Click  |
| Erase         | Right Click |
| Notebook      | E           |

## Technical Details

- Built with Unity
- Uses Unity Input System
- Custom systems:
  - LIDAR raycast grid with sweep timing
  - Texture-based drawing system
  - Procedural handwriting renderer
  - Trigger-based objective tracking

## Current State

Work in progress.

Planned improvements:
- Audio design (wind, distant movement)
- Narrative events
- Multiple locations / areas
- Expanded notebook behaviour
- Ending sequence

## Inspiration

- Return of the Obra Dinn (visual abstraction)
- Scanner Sombre (LIDAR mechanics)
- Analog horror / liminal spaces

## Author

Alistair Bishop

## License

This project is for educational and portfolio purposes.
