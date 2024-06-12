## Project Description:

This project is a simulation model developed in NetLogo 6.4. It aims to simulate residential segregation patterns based on income levels using an agent-based modeling approach. The model allows users to explore how various factors, such as housing affordability and neighborhood preferences, contribute to the spatial distribution of different socioeconomic groups within an urban area.

## Installation:

1. Make sure to install NetLogo from the official source: [NetLogo Download Page](https://ccl.northwestern.edu/netlogo/download.shtml)
2. After installing NetLogo, download the project files.
3. Open the archive 'Model.nlogo' by following these steps:
   - Open NetLogo.
   - Navigate to `File > Open` and select the 'Model.nlogo' file from your file system.

## Usage:

1. Open the 'Model.nlogo' file in NetLogo.
2. Modify the parameters according to your preferences. Below are the descriptions of each parameter:
   
   - **density_poblacion:** A normalized measure indicating the population density on the grid.
   - **actualizacion_costos:** A measure determining how often the housing prices will be updated (in ticks).
   - **presupuesto_vivienda:** A normalized measure indicating the percentage of an agent's income allocated to housing expenses.
   - **similitud_requerida:** A normalized measure indicating the level of similarity required for an agent to be satisfied with its neighborhood.
   - **alpha:** A weight determining the magnitude of the housing price adjustment.
   - **precio_inicial:** The initial cost of all patches (housing units), also serving as the lower bound for housing prices.

3. After setting the parameters, press the 'set' button and then the 'go' button to run the model.

## Parameters:

- **density_poblacion:** Range: [0,1]. A measure of population density normalized to fit within the range [0,1]. Higher values indicate denser populations.
- **actualizacion_costos:** Range: [1,24]. A measure determining how often the housing prices will be updated, expressed in ticks. Larger values result in less frequent updates.
- **presupuesto_vivienda:** Range: [0,1]. A normalized measure indicating the percentage of an agent's income allocated to housing expenses. A value of 1 indicates that the entire income is allocated to housing.
- **similitud_requerida:** Range: [0,1]. A normalized measure indicating the level of similarity required for an agent to be satisfied with its neighborhood. Higher values indicate a higher level of similarity required for satisfaction.
- **alpha:** Range: [0,1]. A weight determining the magnitude of the housing price adjustment. Higher values result in more significant adjustments to housing prices.
- **precio_inicial:** Range: [1000,10000]. The initial cost of all patches (housing units), also serving as the lower bound for housing prices. 

## Running the Model:

1. After setting the parameters, press the 'set' button.
2. Press the 'go' button to run the model simulation.

