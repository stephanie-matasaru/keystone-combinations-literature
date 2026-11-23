# KeySDL: sparse dictionary learning for keystone microbe identification from steady-state observations using a dynamical-systems model
**Citation:** Gordon2026KeySDL · **PDF:** papers/microbiome/Gordon2026KeySDL.pdf
**Read:** bioRxiv preprint version (10.1101/2025.08.07.669165)

## What it's about
Identifies keystone microbes by assuming the community follows generalized Lotka-Volterra (GLV) dynamics and that each observed sample is a steady state, so no numerical integration is needed. GLV parameters (interaction matrix A, growth rates r) are fitted with sparse dictionary learning. Keystoneness (K_BC) = Bray-Curtis dissimilarity between the full steady state and the steady state after removing one microbe. A self-consistency score checks whether GLV fits the data.

Validated on simulated GLV communities (50 microbes), a 14-member gut SynCom with single dropouts, and a 25-member Arabidopsis root SynCom with single dropouts. Predicted keystoneness correlated with measured keystoneness in both experiments (rho = 0.71 in vitro, 0.56 in planta).

## What's relevant for my work
- Removal impact is computed from steady states, so it's cheap to evaluate -> usable as the objective function when searching over combinations.
- Co-occurrence network metrics (degree, betweenness) did not correlate with keystoneness, in simulations or in either experimental dataset -> centrality is a weak baseline.
- In both experimental datasets, keystoneness tracked abundance with no strongly disproportionate keystones.
- Future work explicitly lists evaluating combinatorial effects, including the keystoneness of microbe combinations -> the gap my thesis addresses.

## Used for
Objective function, motivation (research gap), baselines, real data (14-member gut SynCom).

## Limits
Strong GLV assumption (acknowledged as an approximation); assumes constant growth rates and interactions across samples; only single-species dropouts; only two experimental datasets. Code availability not stated in the preprint; check the published version.
