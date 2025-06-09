# cmplxsy_prey-pred

## WHAT IS IT?

(a general understanding of what the model is trying to show or explain)

This model is a simulation of a simple predator-prey ecosystem. Our group has modeled orcas vs seals in an ocean.

## HOW IT WORKS

(what rules the agents use to create the overall behavior of the model)

Two different kinds of agents, orcas and seals, wander around the environment. Each step requires energy by each agent. All agents move towards their food source. In this case, orcas try to "find" seals, and seals try to "find" silverfish/fish. Silverfish are represented as grey patches. Both seals and orcas must eat food in order to replenish energy. Every few ticks, the amount of "food" patches replenish. When orcas or seals run out of energy, they die. 

## HOW TO USE IT

(how to use the model, including a description of each of the items in the Interface tab)

1. Adjust the population settings, and individual prey and predator settings, as needed. 
2. Click the "setup" button.
2. Click the "go" button to start the simulation.

GLOBAL PARAMS:
- reproduction-cost: Dictates how much energy does it take from an agent to reproduce. (only one needed per reproduction. This model does not follow rules like needing a male and female to reproduce.)
- initial-number-food: During setup, this dictates how much food patches are spawned in the environment.
- food-respawn-time: Dictates how many ticks are needed before food begins to respawn.
- max-food: Dictates how many % of the entire environment are food allowed to spawn in. If the amount of food patches reaches a number below this variable's value, then food is allowed to respawn.
- follow-food?: A boolean value that dictates whether or not agents will move towards their food source or not.
- initial-number-seals: Dictates the initial number (not percentage) of seals to be spawned upon setup)
- seals-food-gain: Agents gain a certain amount of energy points upon eating a food patch. This dictates how many points they get.
- max-seals: Dictates the max number of seals at a time. If the amount of seals is below this threshold, then reproduction is allowed. Each reproduction takes a certain amount of energy.
- initial-number-orcas: Dictates the initial number (not percentage) of orcas to be spawned upon setup)
- orcas-food-gain: Agents gain a certain amount of energy points upon eating a food patch. This dictates how many points they get.
- max-orcas: Dictates the max number of orcas at a time. If the amount of orcas is below this threshold, then reproduction is allowed. Each reproduction takes a certain amount of energy.
