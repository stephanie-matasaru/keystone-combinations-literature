# Deciphering microbial interactions and detecting keystone species with co-occurrence networks
**Citation:** Berry2014CoOccurrence · **PDF:** papers/microbiome/Berry2014CoOccurrence.pdf

## What it's about
Simulates microbial communities with gLV models and known interaction networks (Erdos-Renyi, Watts-Strogatz, Barabasi-Albert, Klemm-Eguiluz; ~100 species), then builds co-occurrence networks from the simulated abundances and checks how well they recover the true interactions. Habitat filtering was the most damaging factor for accuracy; hub-heavy networks produced the most spurious correlations.

## What's relevant for my work
- Keystoneness grew with the number of indirectly affected species (r^2 = 0.94), not with the number of direct interactions -> direct-link measures like degree miss keystones.
- Co-occurrence networks can be misleading -> supports using a dynamical model (gLV) instead of correlation networks.
- Same simulation idea as my setup: gLV communities with known structure as ground truth.

## Used for
Motivation (why centrality/co-occurrence is weak), synthetic data design, related work.

## Limits
Simulation only; steady-state and network-model simplifications; real sequencing biases not simulated. In co-occurrence networks, some topological features (high mean degree, closeness, transitivity; low betweenness) did help classify keystones (~85%), so not all topology is useless.
