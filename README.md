# ConsenCUS Block - CO2 Absorption and Regeneration Simulation

## Overview
The **ConsenCUS Block** is a custom simulation block written in **ACM (Aspen Custom Modeller)** and integrated within **ASPEN**. This block is designed to model the entire process of CO₂ absorption by an absorber and its subsequent regeneration (desorption) through an **electrochemical cell**. It allows for detailed simulation of CO₂ capture and release processes in systems using electrochemical methods for regeneration.

## Features
- **Absorption Process Simulation**: The block simulates the process of CO₂ absorption within an absorber, considering various thermodynamic and kinetic factors.
- **Regeneration (Desorption) Process**: Models the regeneration (desorption) of CO₂ through an electrochemical cell, focusing on the efficiency and performance of the electrochemical reactions.
- **Integration with Aspen**: Fully integrated within **Aspen Plus**, allowing for seamless interaction with other blocks and enabling the simulation of complex systems.
- **Customizable Parameters**: Provides a flexible and customizable approach to simulating CO₂ absorption and regeneration processes, with tunable parameters for specific applications.

## Key Components
### Absorber Simulation
- Models the interaction between CO₂ and the absorption solvent.
- Includes the heat and mass transfer effects within the absorber.
- Optimized to simulate realistic absorber dynamics.

### Electrochemical Regeneration (Desorption)
- Simulates the electrochemical cell used to regenerate CO₂ from the solvent.
- Accounts for current density, voltage, and potential losses.

## Installation
1. Ensure that you have **Aspen Plus** installed on your machine.
2. Install **Aspen Custom Modeller (ACM)** for custom block development.
3. Add the ConsenCUS block to your Aspen Plus project:
   - Navigate to the **Custom Blocks** section in Aspen Plus.
   - Import the **ConsenCUS Block** file.
4. Compile the block within ACM, ensuring no errors in the code before use.

## Usage
### Add the Block to Your Flow Sheet
- Drag and drop the **ConsenCUS Block** into your Aspen Plus simulation.
- Connect the required input and output streams for CO₂ absorption and desorption processes.

### Input Parameters
- Define the solvent properties for CO₂ absorption.
- Set the operating conditions for the absorber (e.g., temperature, pressure, flow rate).
- Configure the electrochemical cell parameters for CO₂ regeneration (e.g., current density, number of cell, number of stack,...).

### Run Simulation
- Execute the simulation in **Aspen Plus**.
- Analyze the results of CO₂ capture and regeneration, focusing on efficiency, energy consumption, and CO₂ recovery.

## Outputs
- CO₂ absorption rate in the absorber.
- Energy consumption and efficiency of the electrochemical cell.
- Regenerated CO₂ flow rate and purity.
- Process temperature and pressure profiles.

## Troubleshooting
### Error: Block Not Compiling
- Check for syntax errors in the ACM code. Review logs for specific issues.
- Ensure all required libraries are correctly imported and referenced.

### Simulation Results are Unstable
- Verify input parameters, such as flow rates, temperatures, and pressures.
- Check for unrealistic values or boundary conditions that could lead to instability in the simulation.

## License
This software is provided for academic, research, and industrial use under the terms of the accompanying license agreement. Redistribution or modification of the software without permission is prohibited.

## Contact
For any questions or support, please contact the development team at RCCS resrach center, Heriot-Watt University.

