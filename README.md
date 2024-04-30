[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/234bMY4A)

# Community Detection in Bike Sharing Data

This project focuses on applying community detection algorithms to analyze the bike sharing data from the "Databike.csv" dataset.

## Project Overview

The goal of this project is to identify communities or clusters within the bike sharing network using two popular community detection algorithms: Girvan-Newman algorithm and Louvain algorithm.
## User Defined Functions
1 bikeNetwork
2 networkStats
3 mapPlot
4 heatMapPlot
5 centralityBetweennes
6 communityLouvain
7 communityGirvanNewman
 
The project involves the following steps:

1. Data preprocessing: The dataset is loaded and cleaned, handling missing values and outliers.
2. Network construction: The bike sharing data is transformed into a graph representation, where nodes represent bike stations and edges represent bike trips between stations.
3. Girvan-Newman algorithm: The Girvan-Newman algorithm is applied to the network to detect communities.
4. Louvain algorithm: The Louvain algorithm is also applied to the network to detect communities.
5. Visualization: The detected communities are visualized on a map using the Folium library.
6. Analysis: The results of the two community detection algorithms are compared and analyzed.

## Repository Structure

The repository contains the following files:

1. `DSAideathon.ipynb`: The Jupyter Notebook file containing the code for the project.
2. `Databike.csv`: The dataset used for the project.
3. `README.md`: This file, providing an overview of the project.

## Dependencies

The project requires the following Python libraries:

- `numpy`
- `pandas`
- `networkx`
- `matplotlib.pyplot`
- `folium`
- `community`

You can install these dependencies using `pip` or `conda`:

```
pip install numpy pandas networkx matplotlib folium python-louvain
```

## How to Run

1. Clone the repository to your local machine.
2. Open the `DSAideathon.ipynb` file in a Jupyter Notebook environment.
3. Run the cells in the notebook to execute the code and generate the results.

## Results

The project's main results are:

1. Identification of communities within the bike sharing network using the Girvan-Newman and Louvain algorithms.
2. Visualization of the detected communities on a map using Folium.
3. Comparison and analysis of the two community detection algorithms.

The insights gained from this analysis can be used to improve the bike sharing system, such as optimizing station locations, balancing bike distribution, and enhancing user experience.

## Conclusion

This project demonstrates the application of community detection algorithms to analyze and understand the structure of a bike sharing network. The results provide valuable insights that can be leveraged to enhance the efficiency and effectiveness of the bike sharing system.
