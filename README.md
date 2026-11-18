# OOAD Diagrams: Panda Bamboo Jump

This folder contains Object-Oriented Analysis and Design (OOAD) diagrams for the **Panda Bamboo Jump** game, a browser game where a panda dodges falling rocks by jumping between three bamboo lanes.

## Diagrams

| # | Diagram | File | Purpose |
|---|---|---|---|
| 1 | Class Diagram | [01_ClassDiagram.md](01_ClassDiagram.md) | Shows the classes, their attributes and methods, and how they relate |
| 2 | Object Diagram | [02_ObjectDiagram.md](02_ObjectDiagram.md) | Shows example instances of the classes with their current values |
| 3 | Component Diagram | [03_ComponentDiagram.md](03_ComponentDiagram.md) | Shows the main parts of the system and their dependencies |
| 4 | Use Case Diagram | [04_UseCaseDiagram.md](04_UseCaseDiagram.md) | Shows what the player can do with the game |
| 5 | Activity Diagram | [05_ActivityDiagram.md](05_ActivityDiagram.md) | Shows the step-by-step game flow, including decisions |
| 6 | Sequence Diagram | [06_SequenceDiagram.md](06_SequenceDiagram.md) | Shows the order of messages between objects over time |

## How to View the Diagrams

GitHub renders the Mermaid diagrams automatically when you open a file. You can also paste the Mermaid code into [mermaid.live](https://mermaid.live) to view or edit it.

## Summary of the System

- **Player** controls the panda with the left and right arrow keys or on-screen buttons.
- **Game** manages the score, lives, speed, and the game state (start, playing, game over).
- **Panda** moves between three lanes and jumps when it changes lanes.
- **Rocks** (obstacles) fall down the lanes. Hitting one costs a life. Every 10 rocks dodged increases the speed.
- The game ends when all 3 lives are lost.
