# lhloptimisation

Optimising instrumentation weights in [Witek et al. (2014)](https://doi.org/10.1371/journal.pone.0094446) polyphonic variant on the [Longuet-Higgins & Lee (1984)](https://psycnet.apa.org/record/1985-19235-001) syncopation index.

**Why do we assume the original instrumentation weights are the most appropriate for every experiment?**

Simply uses black-box Bayesian optimisation to derive two- and three-stream syncopation weights that minimise Akaike information criterion (AIC) for a simple OLS linear regression model.
