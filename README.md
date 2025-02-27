# Virtual World Simulator

## Description 🌍🎮

This project is a **turn-based virtual world simulator** implemented in Java. The world consists of a two-dimensional grid where various organisms, including plants and animals, interact. The user can control a **human character**, while other organisms behave according to predefined rules.

The application features a **graphical user interface (GUI) using Java Swing**, allowing users to visualize and interact with the virtual world.

## Features 🦁🌱

- **Turn-based simulation** where organisms act based on their initiative.
- **Animals move and interact**, some engaging in fights, while plants remain stationary.
- **Special abilities for the human character**, controlled via keyboard input.
- **Custom world size configuration** (default: 20x20 grid).
- **Collision handling** based on organism strength and special properties.
- **Different species of animals and plants**, each with unique behaviors.
- **Ability to save and load the world state from a file.**

## Installation & Requirements 🛠️

### Prerequisites

- Java Development Kit (JDK) 8 or later
- Java Swing (included in JDK)

### Setup & Running the Application

1. **Clone or download the repository**
   ```sh
   git clone https://github.com/Vincenzo0611/Simulator.git
   cd Simulator/src
   ```
2. **Compile the project**
   
   If an error occurs, simply run the same command again.
   ```sh
   javac *.java
   ```
   ```sh
   javac *.java
   ```
3. **Run the application**
   ```sh
   java Main
   ```

Alternatively, you can use an IDE like **IntelliJ IDEA** or **Eclipse**:

- Open the project.
- Set `Main.java` as the entry point.
- Click **Run**.

## Controls 🎮

- **Arrow keys** – Move the human character.
- **Special ability key** – Activate the human's unique skill (duration: 5 turns, cooldown: 5 turns).
- **Button-based controls** – Navigate turns and interact with the simulation.

## Code Structure 🏗️

The project follows **object-oriented programming (OOP) principles**, with a hierarchical class structure:

### Core Classes:

- `World` – Manages the grid, organisms, and simulation logic.
- `Organism` – Abstract class representing all life forms.
  - `Animal` (subclass) – Moving organisms.
    - `Wolf`, `Sheep`, `Fox`, `Turtle`, `Antelope`, `CyberSheep` (each with unique behaviors).
  - `Plant` (subclass) – Stationary organisms.
    - `Grass`, `Dandelion`, `Guarana`, `DeadlyNightshade`, `Hogweed` (with special effects).
- `Human` – Player-controlled entity with special abilities.
- `GUI` – Handles graphical representation using Swing.

## License 📜

This project is released under the MIT License.

---

Enjoy simulating your own **virtual world**! 🚀🌟

## GUI Screenshot 📸
![ GUI Screenshot](https://github.com/user-attachments/assets/7c2b185e-aa6b-4cf5-be22-6a9013729699)


