# Botany Garden Simulator 🌸

## Overview

**Botany Garden Simulator** is a Python-based simulation tool designed to model seasonal blooming patterns of various flowers. The simulation leverages synthetic data to visualize and analyze how different flowers bloom across the seasons, providing insights into flower growth and garden management.

This tool is built using Python and optimized for use in **Jupyter Notebooks** and **Google Colab**. It allows users to simulate seasonal bloom patterns, adjust flower attributes, and visualize growth dynamics.

## Features

- **Flower Class Simulation**: Define flowers with attributes like bloom season, color, and height.
- **Seasonal Blooming Simulation**: Track when flowers bloom in different seasons (Spring, Summer, Fall, Winter).
- **Visualization**: Plot flower blooming patterns and garden growth with **Matplotlib**.
- **Synthetic Data**: Generate realistic but synthetic data for experimenting with different garden scenarios.
  
## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/[your_username]/BotanyGardenSimulator.git
Navigate to the project directory:

cd BotanyGardenSimulator
Install required dependencies:


pip install -r requirements.txt
Usage
Open the Jupyter Notebook or Google Colab file:

garden_simulation.ipynb

Run the notebook cells sequentially to simulate flower blooming patterns across different seasons.

Modify the flower attributes or seasons to test various blooming scenarios.

# Example: Define a flower and check its blooming season
flower = Flower(name="Tulip", color="Red", bloom_start="Spring", bloom_end="Summer", avg_height_cm=30)
print(flower.is_blooming("Spring"))  # Output: True
Contribution
Contributions are welcome! Feel free to fork the repository and submit pull requests. If you find any bugs or have suggestions for new features, please open an issue.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Inspiration from various seasonal bloom models

Thanks to the open-source community for their libraries and tools
