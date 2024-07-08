
# NEAT Car AI Simulation using Pygame

This repository contains code for simulating autonomous cars using NEAT (NeuroEvolution of Augmenting Topologies) and visualizing the simulation using Pygame.

## Overview

The simulation involves creating a population of cars, each controlled by a neural network evolved using NEAT. Cars navigate a map and avoid obstacles represented by border colors, while maximizing distance covered and time survived.

## Dependencies

- Python 3.x
- NEAT-Python
- Pygame

## Files

- `main.py`: Main script to run the NEAT simulation with Pygame visualization.
- `car.png`: Image file representing the car sprite.
- `map.png`, `map2.png`, `map3.png`, `map4.png`, `map5.png`: Maps used in the simulation.
- `config.txt`: NEAT configuration file defining genome and population settings.
- `readme.md`: This file, providing an overview of the project.

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/NoobDip/2D_Autonomous_Vehicle_Sim.git
   cd 2D_Autonomous_Vehicle_Sim
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the simulation:
   ```
   python main.py
   ```

4. During simulation:
   - Press `SPACE` to toggle radar visualization.
   - Press `RIGHT ARROW` to change the map randomly.
   - Press `Q` to quit the simulation.

## NEAT Configuration

The NEAT configuration (`config.txt`) specifies genome structure, fitness calculation, and evolution parameters. Modify this file to adjust evolutionary settings.

## Visualizations

The simulation displays cars navigating the map, with radar lines showing obstacle detection. Generation and alive car counts are displayed on the screen.

