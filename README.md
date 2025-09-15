# Dunestorm

**Dunestorm** is a text-based adventure game built in Python.
Players explore a desert, find key items, and try to rescue the *Desert King*. The game uses menus for navigation, tracks player progress, and keeps scores.

## Features

- **Written in Python 3**
- **Menu-driven interface:** Players can log in, create profiles, view instructions, or play the game
- **Player accounts:** Usernames, passwords, and high scores stored in dictionaries
- **Inventory & Resources:** Tracks water, food, weapons, and special items
- **Grid-based map:** 10x10 coordinate system for moving around the desert
- **Random events:** Hunting, sandstorms, and item discoveries use the `random` module
- **Score system:** Players earn points for exploring and completing objectives

## Gameplay Mechanics

- **Exploration:** Move north, south, east, or west on the grid map
- **Resource management:** Water and food decrease as you travel
- **Events & Challenges:** Sandstorms, NPC interactions, and finding key items
- **Final Goal:** Collect all key items to access the *Pyramid* and rescue the *Desert King*

## Technical Details

- **Data Structures:**
  - `dict` for users and high scores
  - `list` for inventory, days passed, and discovered locations
- **Functions:** Each menu and game feature is its own function
- **State Tracking:** Player location, resources, and score are updated in real time
- **Input Validation:** Checks user inputs to prevent errors and crashes