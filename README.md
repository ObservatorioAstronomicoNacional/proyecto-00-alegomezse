[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Vj4z-TUu)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=19010178)
# proyecto00
Proyecto 00. Métodos Numéricos Básicos
# Satellite Orbit Simulation

This Python script simulates the orbit of a satellite using Kepler's laws. It computes the satellite’s position at a given time, plots its full orbital path, and calculates when the satellite reaches a specified radial distance.

## Features
- Solves Kepler’s equation using the Newton-Raphson method.
- Computes radial and angular positions over time.
- Plots the orbit in Cartesian coordinates.
- Calculates the time when the satellite reaches a specific radial position.

## Requirements
- numpy
- matplotlib
- astropy

Install with:
pip install numpy matplotlib astropy

markdown
Copiar
Editar

## Usage
- `keplerSolver(t_obs)`: Solves Kepler’s equation for eccentric anomaly.
- `position(t_obs)`: Returns radial and angular position of the satellite.
- `orbit()`: Plots one full orbital period.
- `date(r0)`: Calculates the time the satellite reaches a given radial distance `r0`.

## Example
- Calculates the satellite position at a specific time `t`.
- Plots the full orbital path.
- Determines the time when the satellite reaches a given distance `r0`.
