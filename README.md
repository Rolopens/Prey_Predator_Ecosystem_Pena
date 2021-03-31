## WHAT IS IT AND HOW IT WORKS?

This agent based model explores the prey-predator relationship through cats and mice. In the model, both cats and mice move around randomly in the world. However, each time they move, they use up energy. If they run out of energy, they die. Mice gain energy by eating the food from the food patches found in the world (the yellow patches) while the cats gain energy by eating the mice.  

## HOW TO USE IT

1. Adjust the slider parameters or use the default settings.
3. Press the SETUP button.
4. Press the GO button to begin the agent based model simulation.
5. View the Populations of the Cats and Mice in the plot as well as the amount of food supply there is for the mice in the second plot.

Parameters for both cat and mouse agents:
- MAX-ENERGY: The max amount of energy a cat or mouse can have

Parameters for cat agents:
- INITIAL-CAT-POPULATION: At setup time, the amount of cats generated in the world is between 1 and this value
- INITIAL-CAT-ENERGY: At setup time, cats are given an energy value between 1 and this value
- ENERGY-FROM-MICE: The amount of energy the cat agents get from eating a mouse agent
- CAT-REPRODUCE: The probability of a cat reproducing at each time step (max of 20%)

Parameters for mouse agents:
- INITIAL-MICE-POPULATION: At setup time, the amount of mice generated in the world is between 1 and this value
- INITIAL-RAT-ENERGY: At setup time, mice are given an energy value between 1 and this value 
- ENERGY-FROM-FOOD: The amount of energy the mice agents get from eating food
- MICE-REPRODUCE: The probability of a mouse reproducing at each time step (max of 20%)

Parameters for food patches:
- FOOD-GROWTH: How long it will take for the food patches to regrow (value between 1 and 50)

## THINGS TO NOTICE

Try playing around with the MAX-ENERGY, INITIAL-POPULATION, and REPRODUCATION-RATE parameters as they can usually determine the dominance of a certain agent population

## THINGS TO TRY

Try changing the parameter values and see how that changes the population increase and decrease of a certain agent over time.

## EXTENDING THE MODEL

Try to add behavior that will balance the population of the two agents as there are instances that the predator (cats) would eat up all the prey (mice) which will lead to the deaths of all predators and prey.

## RELATED MODELS

This model is similar to the Wolf Sheep Predation agent-based model found in the NetLogo models library. 

## CREDITS AND REFERENCES
* Wilensky, U. (2005).  NetLogo Wolf Sheep Predation (Docked Hybrid) model.  http://ccl.northwestern.edu/netlogo/models/WolfSheepPredation(DockedHybrid).  Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.
* Wilensky, U. (1999). NetLogo. http://ccl.northwestern.edu/netlogo/. Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.