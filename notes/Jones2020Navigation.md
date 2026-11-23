# Navigation and control of outcomes in a generalized Lotka-Volterra model of the microbiome
**Citation:** Jones2020Navigation · **PDF:** papers/microbiome/Jones2020Navigation.pdf (arXiv preprint)

## What it's about
Studies how to move a gLV microbiome model between steady states using direct interventions. Case study: an 11-population gLV model of C. difficile infection (fitted by Stein et al. to mouse data). Interventions: single-species probiotics, multi-species fecal transplants, and phage-like removal of one species; antibiotics are modeled as a time-varying input. Uses attractor networks (steady states as nodes) and steady-state reduction (SSR) to find low-cost control protocols.

## What's relevant for my work
- Treats adding/removing species as an intervention on a gLV model -> same modeling frame as my removal problem.
- Multi-species interventions succeeded far more often than single-species ones; single-species phage-style removal was essentially ineffective in their tests -> supports combinations.
- Sometimes the cheapest path goes through intermediate states (sequential interventions) -> idea for discussion / future work.

## Used for
Related work, motivation (combinations), discussion.

## Limits
Preprint (appears to be a book chapter); deterministic, genus-level model fitted to mouse data; only fixed-point steady states; no code mentioned.
