# Degrees of Separation of Celebrities

This project is part of CS50's AI course and explores the concept of **degrees of separation** using graph search algorithms. The goal is to find the shortest path (connection) between two celebrities using their co-starring roles in movies. This is based on the popular "Six Degrees of Kevin Bacon" problem.

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Acknowledgments](#acknowledgments)

## Project Description

The project uses a dataset of actors and movies to construct a **graph**, where:
- Each node represents an actor/actress (celebrity).
- Each edge between two nodes represents a movie where both actors appeared together.

The program then implements **breadth-first search (BFS)** to find the shortest path between two celebrities. For example, you can find how closely connected two actors are through the movies they've worked on.

### Objective
The main objective is to calculate the **degree of separation** between two celebrities. If two celebrities are connected by fewer than 6 degrees, they are said to be closely connected in the entertainment industry.

## Features
- **Graph Search**: Uses breadth-first search to calculate the shortest path between two celebrities.
- **Celebrity Lookup**: Users can input two celebrities' names and find how they're connected through movie appearances.
- **Path Output**: Displays the path of movies and co-stars that link the two actors.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com//LuisDelmo/Degrees_of_separation.git
   cd Degrees_of_separation
   
2. **Install dependencies** (if needed):
- Ensure you have Python 3 installed.


3. **Download the dataset**:
   - The project uses a dataset of actors and movies, which can be downloaded from the course repository or provided source.

## Usage

1. **Run the program**:
   ```bash
   python degrees.py

2. **Input the names of two celebrities** when prompted:
   - The program will compute the shortest path between the two actors in terms of the movies they've co-starred in.
   - Example:
     ```
     Name: Kevin Bacon
     Name: Tom Hanks
     ```
     
3. **Output**:
   The program will display the list of movies and actors connecting the two celebrities, if they are connected.

4. **Exit the program**: The program can be exited at any time by pressing `CTRL+C` or following the exit prompts.

## Technologies Used
- **Python 3**: Main programming language.
- **CS50 AI Library**: Includes helper functions for graph search algorithms.
- **Graph Theory**: Used to calculate degrees of separation between nodes (actors).

## Acknowledgments
This project was inspired by the "Six Degrees of Kevin Bacon" problem and is part of CS50's AI course. Special thanks to the CS50 team for providing the resources and dataset to build this project.


