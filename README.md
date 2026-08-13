# Connect Four — JavaFX

A desktop Connect Four application developed in Java and JavaFX as part of my software design coursework at York University.

This project gave me hands-on experience applying object-oriented design principles, architectural patterns, GUI development, game-state management, and AI decision-making to a complete interactive application.

## Gameplay

The application provides an interactive Connect Four interface with player selection, game-status tracking, undo/redo controls, and save/load functionality.

![Connect Four gameplay](Screenshot%202026-08-12%20222221.png)

## Key Features

- Interactive JavaFX Connect Four board
- Human vs. Human gameplay
- Human vs. AI gameplay
- Multiple opponent strategies
- Greedy AI opponent
- Undo and redo functionality
- Save and load game state
- Restart functionality
- Move counter and game-status messages
- Win and draw detection
- Animated/interactive graphical interface

## Greedy AI

The application includes a Greedy computer-player strategy that evaluates available moves rather than selecting a move randomly.

The strategy prioritizes immediate winning opportunities, attempts to block immediate opponent wins, and otherwise evaluates available positions using board-state heuristics.

![Greedy AI gameplay](Screenshot%202026-08-12%20222540.png)

## Software Design

The project provided practical experience with several software-engineering concepts.

### Model–View–Controller (MVC)

Game state and rules are separated from the JavaFX interface and user interaction logic, reinforcing separation of concerns between the model, view, and controller layers.

### Strategy Pattern

Different opponent behaviours can be selected through interchangeable player strategies, including human, random, and greedy approaches.

### Command Pattern

Game moves are represented through command-based behaviour, supporting undo and redo while maintaining a history of game actions.

## Technologies & Concepts

- Java
- JavaFX
- JUnit
- Object-Oriented Programming
- Model–View–Controller (MVC)
- Strategy Design Pattern
- Command Design Pattern
- Event-driven GUI programming
- Game-state persistence
- Heuristic decision-making
- Unit testing

## My Implementation Work

My work on the project included extending and integrating functionality within a provided academic starter framework. Areas I worked on included:

- JavaFX board, cell, control, and status-view behaviour
- Player/opponent selection and game interaction
- Greedy opponent strategy and move-selection logic
- Command-based move execution with undo/redo support
- Save/load and game-state management
- Event handling and UI behaviour
- Game-status and move-count feedback
- Testing and integration of game functionality

## Academic Integrity

This project was completed as part of EECS 3311 — Software Design at York University using a course-provided starter framework.

To respect academic-integrity requirements, this public repository is a portfolio overview only. Course-provided starter code, assignment materials, tests, and solution source code are intentionally not published.

The screenshots and documentation demonstrate the completed application and describe the software-design concepts and implementation experience gained through the project.

Source code can be discussed or demonstrated privately where appropriate and permitted.
