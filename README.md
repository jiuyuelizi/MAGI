# MAGI — Dependent Bayes with Temporal Ordering
MAGI estimates causal structure and direct effects from pairwise count tables using:
1. a temporal ordering score,
2. dependent-Bayes “lambda” links between predictors,
3. a piecewise-stable total-effect (odds) construction, and
4. backward recursion to obtain direct effects and a logistic link.
This repository includes a reference Python implementation and helper routines for selecting predictors and extracting the induced subgraph from a database.
