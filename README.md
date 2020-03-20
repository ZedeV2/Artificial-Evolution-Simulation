# Artificial-Evolution-Simulation

Javascript simulation of a population evolving over time depending on 3 variables

- Birth Rate (**B**): Chance that a creature appears spontaneously in the world at each timestep.
- Death Rate (**D**): Chance of dying that every creatures has at each timestep.
- Replication Rate (**R**): Chance that a creature replicates itself, adding a copy (*mutation is not implemented yet*) of itself in the world at each timestep (applied to every creatures).
- Crowding Coefficient (**C**): Simulates a finite amount of food for a growing population: if the population is to big for the world to carry more creatures will die at each timestep.

**INTERACTIVE:** Use the integrated sliders to control those variables live.

This simulation is disponible on my website: code.zedev2.io/Evolution.html. To run locally, clone the project and run index.html in your browser.

Graph made using [Plotly](https://plot.ly/javascript/).
