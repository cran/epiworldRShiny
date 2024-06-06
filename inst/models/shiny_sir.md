## SIR Network Model

The SIR Network model is the network version of the Susceptible-Infected-Recovered model. In this version, agents are embedded in a network. The probability of infection is determined by the number of infected neighbors that an agent has.

### Parameters

The SIR model has the following parameters:

- **Disease Name**: The name of the disease being modeled.
- **% of Population Infected**: The percentage of the population that is infected at the start of the simulation.
- **Probability of exposure (daily)**: The probability that an individual will be exposed to the virus on a given day.
- **Recovery probability (daily)**: The probability that an individual will recover from the virus on a given day.
- **Simulation Time (Days)**: The number of days to simulate.
- **Seed**: The seed for the random number generator.
- **Population Structure**: The population structure to use for the simulation.
- **NPIs**: The non-pharmaceutical interventions to use for the simulation.
