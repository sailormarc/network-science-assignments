# ERGMs, robustness and compartmentmental models
This folder contains assignments for a Network Science class I took in the fall semester 2023 at the University of Zurich. It consists of two notebooks, which are joint work with Christian Stoppani. 

## ERGMs & robustness
In this notebook we:
1. Fit Exponential Random Graph Models (ERGM) to the World Trade Web network and investigate their associativity properties,
2. Filter and analyze stock return correlations,
3. Assess by simulation the robustness of different network topologies with respect to random failures and targeted attakcs.

## Compartmental models
In this notebook we simulate the Susceptible-Infected (SI), Susceptible-Infected-Susceptible (SIS) and Susceptible-Infected-Recovered (SIR) dynamics on synthetic and real-life networks and investigate their properties.

## Requirements

To run this project, you'll need to install the required Python packages. You can do this by running the following command:

```bash
pip install -r requirements.txt
```

The notebooks are joint work with Christian Stoppani. They are not runnable as some of the datasets are not publicly available. We include an empty `data/` folder to be consistent with the project's structure implied in the scripts.
