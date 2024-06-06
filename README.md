# Network Science Project - Analysis of Sports Facilities in Estonia

## Overview

This repository contains the work done for a Network Science course project.
The primary focus is on data manipulation and network analysis to derive meaningful insights from a dataset of sports facilities and organizations in Estonia.

## Project Structure

### Initial Setup
- Import necessary libraries and set up the environment for analysis.

### Data Loading
- Load two datasets containing data about sports facilities and sports organizations in Estonia.

### Data Preprocessing
- Convert columns to correct formats, process numerical data, and prepare the data for network analysis.

### Data Analysis
- Perform various network analyses including centrality measures and community detection.
- Visualize and interpret the results.

### Visualization
- Generate visual representations of the network and centrality measures.

## Goals

- To understand the connections and relationships within the data.
- To apply network science methodologies to uncover patterns and insights.

## Data Sources

- JSON files from Eesti spordiregister (Estonian Sports Register).

## How to Execute the Code

### Prerequisites

1. Install Anaconda or Miniconda.
2. Create a new conda environment and install Jupyter Notebook.

### Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/anti1/NS_PROJECT.git
    cd NS_PROJECT
    ```

2. Create a conda environment and install the required packages:

    ```bash
    conda create -n ns_project python=3.10
    conda activate ns_project
    pip install -r requirements.txt
    ```

### Run the Notebook

1. Launch Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

2. Open `project.ipynb` and run the cells sequentially.

### Notes

- Ensure the `spordiehitised.json` and `spordiorganisatsioonid.json` files are present in the root directory.
- The processed CSV files will be saved in the `csv_files` directory.

## Results

- The `media` folder contains visualizations generated from the analyses.
- The `gephi` folder contains graph files that can be opened with Gephi for further exploration.
- The `csv_files` folder contains csv files generated during and after preproccesing steps.

## Acknowledgments

- Data sourced from Eesti spordiregister (Estonian Sports Register).