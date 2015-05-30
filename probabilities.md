# Bayes Network
* Influence Diagrams

Used for diagnostics, prediction
Assists in reasoning between observable values and hidden causes
A joint probability network

Nodes linked by arcs
A ``Child Node`` is influenced by ``Parent Node``

* Binary Events
* Probability
* Simple Bayes Networks
* Conditional Independence
* Bayes Netorks
* D-Separation
* Parameter Counts

Bayes Networks Underly:
* Particle Filters, HMM, MDP, POMDPs, Kalman Filters


# Probabilities
## Coin
```
P(HEADS) = 0.5
P(TAILS) = 0.5
```
## Loaded Coin
```
P(HEADS) = 0.25
P(TAILS) = 0.75
```
# Independent Coin Flips
```
P(HEADS,HEADS,HEADS) = 0.5 * 0.5 * 0.5 = 0.125
```
# 

```
Xi = result of coin flip Xi={H,T}
P(X1 = X2 = X3 = X4) = 1 * 0.5 * 0.5 * 0.5 = 0.125

P(HEADS,HEADS,HEADS) + P(HEADS,HEADS,HEADS)

P([X1,X2,X3,X4] contains  >= 3 H) = 

P(HEADS,HEADS,HEADS,HEADS) 0.0625 + 
P(TAILS,HEADS,HEADS,HEADS) 0.0625 + 
P(HEADS,TAILS,HEADS,HEADS) 0.0625 + 
P(HEADS,HEADS,TAILS,HEADS) 0.0625 + 
P(HEADS,HEADS,HEADS,TAILS) 0.0625 = 0.3125

```

# Independence
For independent variables
```
X (Upside down T) Y   : P(X)P(Y) = P(X,Y)
            product of marginals = joint possibility
```

# Dependence
Second event is influenced by result of first event
So there are separate paths
The total probability of the path 










