# Elementary Dynamical Simulation of Hurricane Winds using Rankine Vortex

## Overview
I developed this simulation as my final project for EPS 109 (Computer Simulations in Earth and Planetary Sciences) at UC Berkeley. It provides an elementary dynamical simulation of hurricane winds using the Rankine vortex model. The Rankine vortex is a simple and surprisingly accurate representation of rotational fluid flow, making it a valuable tool for modeling intense wind vortices such as hurricanes.

## Project Contents
1. **Simulation Code**: A Jupyter notebook (`Elementary_Dynamical_Simulations_of_Hurricane_Winds_using_Rankine_Vortices.ipynb`) implementing the Rankine vortex model to simulate hurricane wind fields.
2. **Presentation**: A PDF presentation (`Elementary Dynamical Simulation of Hurricane Winds using Rankine Vortex.pptx.pdf`) explaining the simulation code, including verification and documentation.

## Rankine Vortex Model
- **Definition**: The Rankine vortex model provides a velocity vector at a given radius \( r \) from the center of the vortex. It is characterized by a central core where the fluid velocity is constant and equal to the vortex's maximum velocity. Outside the core, the velocity decreases radially until it becomes zero.
- **Parameters**:
  - **\( a \)**: Radius of the vortex-core.
  - **\( \Gamma \)**: Circulation strength.
  - **\( r \)**: Distance from the center.

## Why Rankine Vortex for Hurricane Winds?
The Rankine vortex is an excellent representation of hurricane winds due to the consistent and relatively uniform nature of hurricane circulations. This model's simplicity allows for effective simulations of such complex systems.

## Features
- **Animation**: The project includes animations of the hurricane wind field, demonstrating the motion of the eye and wind patterns.
- **Parameter Adjustments**: Users can modify parameters like circulation strength and vortex-core radius to observe different wind field behaviors.
- **Verification**: The simulation results are compared with established models and literature to validate accuracy.

## References
1. Holland, G. J., Belanger, J. I., & Fritz, A. (2010). A Revised Model for Radial Profiles of Hurricane Winds. Mon. Wea. Rev., 138, 4393-4401. [DOI: 10.1175/2010MWR3317.1](https://doi.org/10.1175/2010MWR3317.1)
2. Giaiotti, D., & Stel, F. (2006). The Rankine Vortex Model. Regional Meteorological Observatory, Visco, Italy.
3. Dutkiewicz, M. (2019). Models of strong wind acting on buildings and infrastructure. IOP Conf. Ser.: Mater. Sci. Eng., 471, 052030.

## License
This project is licensed under the MIT License.
