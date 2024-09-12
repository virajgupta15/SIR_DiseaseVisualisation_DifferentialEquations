# SIR Model Disease Spread Simulation

This Python project simulates the spread of a disease using the **SIR (Susceptible-Infected-Recovered)** model, a standard epidemiological model. The model is implemented using ordinary differential equations (ODEs) to track the progression of individuals between three groups: Susceptible (S), Infected (I), and Recovered (R).

## Features

- **SIR Model Equations**: Implements the system of differential equations that govern the disease spread.
- **Numerical Solver**: Utilizes `scipy.integrate.solve_ivp` to solve the ODEs numerically over a given time span.
- **Visualization**: Uses Matplotlib to plot the populations of Susceptible, Infected, and Recovered individuals over time.

## Installation

To run the code, you need to have Python 3 installed along with the following libraries:
- NumPy
- SciPy
- Matplotlib

You can install the dependencies using pip:

```bash
pip install numpy scipy matplotlib
```

## Usage

1. Clone the repository or download the script.
2. Open a terminal or command prompt and navigate to the directory containing the script.
3. Run the script:

```bash
python sir_model_simulation.py
```

The program will simulate the disease spread over a specified time period and display a graph showing the population of susceptible, infected, and recovered individuals.

## Parameters

- **`beta`**: Infection rate, representing the probability of transmission per contact between susceptible and infected individuals.
- **`gamma`**: Recovery rate, indicating the rate at which infected individuals recover and become immune.
- **Initial SIR values**: Set the starting populations for Susceptible, Infected, and Recovered.

You can modify these parameters directly in the code to observe how they affect the disease spread dynamics.

