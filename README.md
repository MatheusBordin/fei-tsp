## Overview
This repository contains a generic Python implementation of a Genetic Algorithm to solve the Travelling Salesman Problem (TSP). Geographic coordinates of cities are provided as input to generate a edge-weighted complete graph where the weights are the distance between the cities in kilometers.

## Requirements
Python 3.

## Instructions
1. Clone the repository and navigate to the downloaded folder.
    ```bash
    git clone https://github.com/matheusbordin/fei-tsp.git
    cd fei-tsp
    ```

2. Install required packages:
	```bash
	pip install -r requirements.txt
	```

3. Navigate to the src folder and execute:
    ```bash
    cd src
    python main.py -v 1 --pop_size 1000 --tourn_size 40 --mut_rate 0.03 --n_gen 20 --cities_fn '../data/cities.csv'
    ```

