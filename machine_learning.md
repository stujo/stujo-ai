# Machine Learning

* Machine Learning helps find Bayes Networks from Data

### Discovery

What?
* Parameters
* Structure
* Concepts

From?
* Supervised Learning - Labelled Data
* Unsupervised Learning - Untagged Data
* Reinforcement Learning - Feedback

For?
* Prediction
* Diagnostics
* Summarization

How?
* Passive
* Active
* Online
* Offline

Outputs?
* Classification - finite values
* Regression - continuous values

Details?
* Generative - Generate Data
* Discriminative - Discriminate different data

## Supervised Learning

* ``X`` Predictor
* ``Y`` Tag or Label

Learn from existing data
```
X1,X2,X3,...,Xn => Y
....
....
X201,X202,X203,...,Xn => Y20

```

Generate a function:

```
f(Xm)=>Ym
```

Where ``Xm`` is a future dataset

Overfitting => Function too Complex, doesn't perform well in reality due to overfitting error

We need a represenation of the subject

e.g. Reduce Email Content to a ``Bag of Words``

### Laplace Smoothing
Adds a factor ``k`` to the probability estimates
```
P(x) = count(x) + k
       -------------
         N + k|x|   
```

where ``|x|`` is the number of classes of x e.g. ``2`` for boolean values

## Unsupervised Learning

