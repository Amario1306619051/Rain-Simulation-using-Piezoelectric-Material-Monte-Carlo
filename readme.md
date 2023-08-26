# Rain Simulation using Piezoelectric Material Monte Carlo

![Rain Simulation](./ezgif.com-video-to-gif%20(1).gif)

This Python program simulates raindrop impacts on a piezoelectric material surface using the Monte Carlo method. It combines the 'pygame' library for visualization and 'matplotlib' for data plotting, providing an interactive and visual representation of raindrop impacts on a surface.

## Features

- Simulates raindrop impacts on a piezoelectric material surface.
- Utilizes the Monte Carlo method to model random raindrop trajectories.
- Generates electrical energy upon raindrop impact on the designated area.
- Tracks and accumulates generated energy over time.
- Displays an interactive visualization of raindrops falling on the surface using 'pygame'.
- Plots a graph using 'matplotlib' to showcase the relationship between time and accumulated energy.
- Simulates different rain intensities to observe their impact on energy generation.

## Requirements

- Python 3.x
- pygame library
- matplotlib library

## How to Use

1. Install the required libraries using the following commands:

```
pip install pygame
pip install matplotlib
```

2. Run the `rain_simulation.py` script:

```
python rain_simulation.py
```

3. Observe the raindrop simulation in the pygame window.
4. After the simulation is complete, a graph will be displayed showing the energy accumulation over time.

## Results

Insert screenshots of the simulation and generated graph here.
![Results](Screenshot%202023-08-26%20at%2011.14.23.png)
Blue line = Theorem result<br>
Red line = Simulation result<br>
X-axis = time
Y-axis = energy

## Simulation Parameters

You can modify the simulation parameters in the script to change raindrop intensity, impact area, piezoelectric material properties, and more. Adjusting these parameters will help you explore the behavior of the piezoelectric material under different conditions.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

This simulation was inspired by the concept of harvesting energy from environmental sources using piezoelectric materials. The Monte Carlo method adds randomness to the simulation, making it more realistic and informative.

Feel free to contribute to and modify the simulation to further enhance its accuracy and features.# Rain-Simulation-using-Piezoelectric-Material-Monte-Carlo
