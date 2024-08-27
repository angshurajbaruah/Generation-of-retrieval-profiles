# Optimal Estimation-based Physical Model - 1D Var Retrieval of Temperature and Humidity Profiles

This repository contains the code and analysis for the research **"Optimal estimation-based, physical model- 1D Var retrieval of temperature and humidity profiles from Passive microwave radiometry over the Indian region."** The project focuses on retrieving atmospheric profiles using the optimal estimation technique and a one-dimensional variational (1D-Var) approach applied to microwave radiometer data.

## Project Overview

The primary objective of this study is to develop a retrieval framework that uses passive microwave radiometry data for estimating temperature and humidity profiles over the Indian region. The retrieval algorithm incorporates a physical model and the 1D Var approach, enabling accurate estimations of atmospheric states from satellite observations.

### Key Features:
- **Data Retrieval**: The code retrieves temperature, brightness, and humidity profiles using passive microwave radiometer data.
- **Optimal Estimation Technique**: Implements an optimal estimation technique to invert radiometric data into physical quantities.
- **Physical Model**: The algorithm uses a forward physical model to simulate the radiometric measurements and compares them with observed data.
- **1D Var Retrieval**: A one-dimensional variational method is employed to estimate the state vector (temperature and humidity profiles) that best fits the radiometric data.
- **Regional Focus**: The study and analysis focus on the Indian region, specifically targeting the influence of these atmospheric profiles on rainfall intensity.

## File Structure

- `data/`: Contains all raw and processed microwave radiometry data used in the retrieval process.
- `notebooks/`: Jupyter notebooks for running analysis and visualization of the retrieval outputs.
- `src/`: Python scripts that implement the optimal estimation and 1D Var retrieval algorithm.
- `results/`: Contains output files with retrieved atmospheric profiles and related analysis.
- `plots/`: Visualizations and plots generated during the analysis.
- `docs/`: Documentation and additional resources, including research papers and references.


