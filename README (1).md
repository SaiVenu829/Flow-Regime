# Reservoir Flow Regimes Simulation

This project simulates and visualizes three fundamental flow regimes in petroleum reservoir engineering:

- **Steady-State Flow**: Reservoir pressure remains constant over time.
- **Unsteady-State Flow**: Reservoir pressure declines exponentially due to transient behavior.
- **Pseudo-Steady-State Flow**: Pressure decreases linearly as boundary effects dominate.

## Project Objectives

- Demonstrate basic pressure-time behavior for different flow regimes using simple Python code.
- Apply concepts from Darcy’s law and reservoir flow theory.
- Generate clear visualizations to understand and compare flow regimes.

## Tools & Technologies

- Python 3.x
- NumPy
- Matplotlib

## How to Run

1. Ensure Python 3 and required libraries are installed:
   ```bash
   pip install numpy matplotlib
   ```

2. Run the script:
   ```bash
   python flow_regimes_simulation.py
   ```

3. View the generated plot or open the saved `flow_regimes_pressure_plot.png`.

## Sample Output

The plot illustrates the difference between:
- **Steady-State**: Flat line (constant pressure)
- **Unsteady-State**: Curved line (rapid pressure drop)
- **Pseudo-Steady-State**: Straight line (linear pressure decline)
