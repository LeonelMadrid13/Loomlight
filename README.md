# Forager-Inspired Sandbox Game

## Description

This project is a **single-player sandbox game** inspired by the popular indie game Forager. The game emphasizes resource gathering, crafting, base building, and exploration in a procedurally generated 2D world. Players start with basic tools and must collect resources to expand their capabilities, build structures, and uncover the mysteries of their environment. The game aims to deliver a relaxing yet engaging experience with simple controls, vibrant pixel art, and a progression system that rewards creativity and exploration.

- Core Features:
  - `Resource Gathering`: Chop trees, mine rocks, and forage for materials scattered across the world.
  - ``Crafting System``: Combine resources to create tools, structures, and items essential for progression.
  - ``Base Building``: Design and construct your home base with furnaces, storage, and other utilities.
  - ``Exploration``: Traverse a diverse landscape of biomes, each with unique resources and visual themes.
  - ``Progression``: Unlock new recipes, tools, and abilities as you gather and craft.

## Step-by-Step Plan for Single-Player Core

1. Refine the Scope
    - Gameplay Focus: Resource gathering, crafting, exploration, and base building.
    - Simplify Mechanics: Start with core loops like harvesting resources and building structures.
    - Art Style: Stick to a simple pixel art style for efficiency.
2. Build Core Mechanics
    - World Generation:
        - Use a grid-based map.
        - Randomly place resources like trees, rocks, and ores.
    - Resource Gathering:
        - Define tools (e.g., axe for trees, pickaxe for rocks).
        - Animate resource depletion (e.g., tree disappearing after chopping).
    - Crafting System:
        - Create a crafting menu.
        - Implement a recipe system to manage resource combinations.
    - Base Building:
        - Allow placing and rotating basic structures (e.g., furnaces, storage).
        - Implement snapping to a grid for easy alignment.
    - Exploration:
        - Create varied biomes or terrain types (optional).
        - Add collectibles or hidden areas to incentivize exploration.
3. Post-Core Expansion
    - Dynamic weather or day-night cycles.
    - Energy or stamina mechanics to limit actions.
    - Simple NPCs or quests for world-building.

## Milestones

- Basic Map Rendering:
  - [ ] Display a grid with grass tiles.
- Add Resources:
  - [ ] Randomly place trees and rocks on the map.
- Biomes:
  - [ ] Implement distinct regions with different terrain and resources.
- Interactive Tiles:
  - [ ] Enable gathering and depletion mechanics.
