
# Particle-in-Cell (PIC) Simulation with Landau Damping

This repository contains a 1D Particle-in-Cell (PIC) simulation that models **Landau damping** in a plasma. Landau damping is a collisionless damping mechanism where plasma waves lose energy to resonant particles, leading to a decay in wave amplitude over time.

## Features:
- **PIC Algorithm**: Self-consistent evolution of charged particles interacting with an electric field in a 1D periodic domain.
- **Landau Damping**: Visualization of charge density oscillations that dampen as energy is transferred to resonant particles.
- **Poisson Solver**: Fourier-based Poisson solver for computing the electrostatic potential and electric field.
- **Initial Perturbation**: Maxwellian velocity distribution with a small sinusoidal perturbation to induce plasma oscillations.
- **Visualization**: Heatmap of charge density evolution over time, demonstrating the gradual damping of plasma waves and particle clumping.

## Getting Started:
1. Clone the repository.
2. Install the required Python libraries (e.g., NumPy, Matplotlib).
3. Run the Jupyter notebook file `PIC_Landau_Damping.ipynb` to observe Landau damping.

## Dependencies:
- **Python 3.x**
- **NumPy**
- **Matplotlib**

## Visualization:
The simulation produces a heatmap of charge density evolution over time, illustrating the key characteristics of Landau damping and phase mixing.

## License:
This project is licensed under the MIT License - see the LICENSE file for details.
