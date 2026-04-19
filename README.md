# ECE 105 Lab 3 — Sensor Data Visualizations

A script and Jupyter notebook that created multiple graphs to demonstrate 
synthetic temperature sensor data and produce publication-quality complete 
visuals using NumPy and matplotlib.

## Installation

1. Activate the ece105 conda environment:
mamba activate ece105

2. Install dependencies:
mamba install -n ece105 numpy matplotlib -y

## Usage

This was used to run the script so that it would generate three whole plots and then save them as a PNG each:

python generate_plots.py

This would produce the `sensor_analysis.png` found in the current directory.

## Output

The script created three subplots:
- **Scatter plot**: Temperature readings from Sensor A and Sensor B over time
- **Histogram**: Overlapping distributions of the sensors with mean lines
- **Box plot**: A side-by-side comparison of sensor distributions

## AI Tools Used

I managed to complete the project using the AI assistant known as Claude (Anthropic), via
claude.ai. This AI would generate code based on the intent comments typed in the script
before (otherwise known as the "explain first" pattern). Before and after completion, all code used was reviewed and understood. In addition to everthing said so far, Claude had the added bonus of explaining individual lines when needed.