# AI-Driven Disaster Evacuation Simulator

A multi-agent simulation system that models emergency building evacuation using A* pathfinding and crowd movement visualization.

## Overview

This project demonstrates how artificial intelligence and simulation techniques can assist in planning safer evacuation strategies during disasters. A grid-based building layout is created where multiple agents attempt to reach the nearest exit using optimal pathfinding.

The system visually simulates crowd movement and evacuation progress in real time.

## Features

- Multi-agent crowd evacuation simulation  
- A* pathfinding algorithm for optimal routing  
- Grid-based building environment  
- Multiple exit navigation system  
- Real-time evacuation progress tracking  
- Animated visualization of agent movement  

## Technologies Used

- Python  
- NumPy  
- Matplotlib  
- NetworkX  

## How the Simulation Works

1. A building layout is generated using a grid structure.
2. Walkable paths and walls define the navigation environment.
3. Multiple agents are randomly placed in the building.
4. Each agent calculates the shortest path to an exit using the A* algorithm.
5. Agents move step-by-step toward the exits until evacuation is complete.
6. The system displays evacuation progress and agent movement visually.

## How to Run

Install required libraries:

pip install -r requirements.txt

Open and run the simulation notebook:

disaster_evacuation_simulator.ipynb

## Applications

This type of simulation can be useful for:

- Emergency evacuation planning  
- Crowd management studies  
- Safety analysis of building layouts  
- Disaster preparedness research  
