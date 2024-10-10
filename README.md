# Thesis

Title: Stock Market Dynamics Using the Bornholdt Model and Various Network Topologies

Overview:

This project simulates the dynamics of the stock market using the Bornholdt model, adapted from statistical physics, to explore investor interactions across different network topologies. The project investigates how these network structures influence market behavior, investor sentiment, and the resilience of financial systems. The simulations are conducted using various network topologies, including original (grid-based), Barabási–Albert, Watts–Strogatz, and scale-free graphs.

Objectives:

To investigate the impact of different network topologies on market behavior and investor interactions.
To analyze investor behavior within these topologies using graph plots and other metrics such as magnetization and returns.
Key Features:

Network Topologies: The project supports multiple network topologies:

Original (Grid-based): A rectangular grid with periodic boundary conditions.
Barabási–Albert Graph: A scale-free network model.
Watts–Strogatz Graph: A small-world network model.
Scale-Free Graph: A network model where the degree distribution follows a power law.
Investor Behavior Simulation: The Bornholdt model is used to simulate the behavior of investors, where each investor's decision to buy or sell is influenced by their neighbors in the network.

Visualizations: The project generates visualizations of the network structures, snapshots of the investor states at various time steps, and plots of the returns and cumulative distribution of returns.

Methodology:

Simulation Parameters:

N: Total number of traders.
width: The width of the grid representing the market.
J: Coupling strength between traders.
alpha: A parameter that influences how an investor's strategy affects the market.
beta: Inverse temperature, influencing the randomness of decisions.
topology: The network topology to be used (original, Barabási–Albert, Watts–Strogatz, scale-free).
ts: Specific time steps at which to capture snapshots of the market state.
warmupiterations: Number of iterations before the actual simulation begins.
simulationiterations: Number of iterations for the actual simulation.
return_plot_x_interval: Interval for plotting returns.
Experiment Setup: Multiple experiments are conducted by varying the network topology and other parameters. The results are saved as images in the results directory.

Results:

The results of each experiment, including network structure snapshots, return plots, and cumulative distribution plots.


