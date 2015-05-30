#Intelligent Agent (Agent)
The program which is using AI

#Perception Action Cylcle
The repeating cycle of the agent using it's sensors and actuators

#Environment
What the sensors could observe

##Types of Environment

### Fully vs Partially Observable
All the sensors can always see the entire environment state vs The history of the sensors inputs can help us understand the environment - Memory is useful in Partially Observable Environments

###Deterministic vs Stochastic Environment
Non-Random vs Randomness involved

###Discrete vs Continuous Environment
Finite vs Infinite number of options

###Benign vs Adversarial Environment
Random Events vs Actively Working against the Agent

| Partially Observable | Stochastic | Continuous | Adversarial |
|----------------------|------------|------------|-------------|
|                      |            |            |             |
|                      |            |            |             |
|                      |            |            |             |


# Algortythms
* Complete - Will find goal in infinite space
* Breadth First
* Uniform Cost First
* Depth First
* Greedy Best First Search
* A* Minimum value of ``f = g + h`` - Best Estimated Total Path Cost First
  * ``g => Path Cost So Far``
  * ``h => Heuristic of final cost``
  * We want h to be optimistic, always less than actual cost (admissable)
* Generating Relaxed Problem
  * Removing constraints 

# Route Finding Problem Definition
* Initial State ``S``
* Available actions for a State ``actions_for(S)`` -> ``[A1,A2,A3,...]``
* Result of Action on a State ``result_for(S,A)`` -> ``S1`` new state
* Have we reached the Goal ``goal_test(S)`` -> ``[true|false]``
* Path Cost -> sum of all Actions on Path
* Step Cost -> cost of Action on a given State for a result State ``step_cost(S,A,S1)``
* State Space
  * Explored
  * Frontier
  * Unexplored

# Search Problem Solving Works When
* Fully Observable
* Known
* Discrete
* Deterministic
* Static

# Implementation
* Path is a ``Linked List`` of state ``Node``s with data
* Frontier - Priority Queue and Set
* Explored - Set 




