# Simulation Setup
This repository contains the configuration files and instructions for running traffic simulations using SUMO (Simulation of Urban MObility). The simulations cover basic scenarios and include an advanced sublane mode for increased lateral resolution.

## Prerequisites
Before running the simulations, make sure you have SUMO installed on your system. You can download it from the official SUMO website.

## Running the Simulations
1. Simple Simulation: to run a basic traffic simulation, use the following command in your command line:

            sumo-gui -c example.sumocfg

This will launch the SUMO graphical interface with the provided configuration file (example.sumocfg).

2. Sublane Mode Simulation
For simulations with increased lateral resolution, enabling the sublane mode, use the following command:

            sumo-gui -c example.sumocfg --lateral-resolution <float>

This mode is particularly useful for scenarios involving multiple 2-wheeled vehicles, overtaking, virtual lane formation, lateral dynamics, dynamic longitudinal gap acceptance during lane changing, and more.

Adjust the example.sumocfg file to tailor the simulation parameters according to your specific requirements.

## Additional Notes
Make sure to check the SUMO documentation for detailed information about available features and configurations.
Feel free to experiment with different parameters in your configuration files to create custom scenarios.
Happy simulating! 🚗🚦