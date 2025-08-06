# Automated-Industrial-Sorting-System-Simulation
# Conveyor Sorting System Simulation - Week 1

## Overview
This project simulates an automated industrial sorting system using Python and Pygame. It models packages moving on conveyor belts, detecting weight and color via sensors, and sorting packages accordingly.

## Role: Main Control Logic Lead
As the Main Control Logic Lead, my responsibility is to develop the central system control logic that governs package sorting by building and managing the state machine that controls sensing, decision-making, and actuator commands.

## Week 1 Deliverables

- **State Machine Diagram:**  
  A visual representation of the system's core control states, including the detection of packages at sensors, sorting decisions based on weight and color, and resetting package states after sorting.

  ![State Machine Diagram](https://github.com/Prabhudev2004/Automated-Industrial-Sorting-System-Simulation/blob/e34cb132f965aec80fe9e3fba4dbf79a5f1b7b53/Screenshot%202025-08-06%20160343.png)

- **Initial Simulation Code:**  
  A Pygame-based Python simulation demonstrating package movement on conveyor belts, sensor detection logic (weight and color), sorting decisions, and basic logging of events.

## How to Run the Simulation

1. Make sure Python 3 and Pygame are installed on your system.
2. Run the `simulation.py` script:

3. The simulation window will open showing moving packages, sensor lines, and real-time sorting actions.

## Project Structure

- `simulation.py` — Main simulation code with package sorting logic.
- `state_machine_diagram.png` — State machine diagram illustrating control logic.
- `README.md` — This file providing project summary.

## Summary of State Machine

The system cycles through these states:

- **Idle / Waiting for Package**: System awaits package arrival at sensors.
- **At Weight Sensor**: Package is measured to decide conveyor diversion.
- **Sorting by Weight**: Package is assigned to a belt/bin based on weight.
- **At Color Sensor**: Package color is detected.
- **Sorting by Color**: Final bin is assigned based on color.
- **Exit/Reset**: Package leaves system and readies for the next cycle.

## Logging and Controls

- Sorting decisions are logged in `system.log`.
- Use keyboard arrows to control belt speed.
- Keys `w`/`e` and `c`/`v` move weight and color sensors, respectively.

---

Feel free to reach out if you have any questions or need further improvements!

