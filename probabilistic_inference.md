# Probabilistic Inference

* Inputs -> Evidence Variables
* Outputs -> Query Variables
* Others -> Hidden Variable

Posterior Distribution -> Probability Distribution

```
P(Q1,Q2,..|E1:e1,E2:e2,...)
```

## Conditional Probability

```
P(+b|+j,+m) = P(+b,+j,+m)/P(+j,+m)

P(+b,+j,+m) = SUM{e SUM{a P(+b,+j,+m,e,a) }  }
P(+b,+j,+m) = SUM{e SUM{a P(+b) P(e) P(a|+b,e) P(+j,a) P(+m,a) }  }

```
