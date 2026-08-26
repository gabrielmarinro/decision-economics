# Monte Carlo

The scenario layer includes stochastic simulation for variable operational events and Google Cloud cost exposure.

## Current implementation

The simulation can run up to **10,000 iterations** and reports a distribution with mean, p50, p90 and p95 outputs.

The model samples event occurrence and cost variation, then aggregates the simulated outcome to expose the range of possible cost consequences.

**Uncertainty → simulation → distribution → decision**
