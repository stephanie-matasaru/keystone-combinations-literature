# Top-down identification of keystone taxa in the microbiome
**Citation:** Amit2023TopDown · **PDF:** papers/microbiome/Amit2023TopDown.pdf
**Read:** bioRxiv preprint version (10.1101/2021.09.02.458706)

## What it's about
Defines keystones by presence-impact: how much a species' presence/absence changes the abundance profile of all other species. Proposes Empirical Presence-Impact (EPI), which estimates this from cross-sectional data by comparing samples where a species is present vs absent (measures D1, D2, Q), with no need to reconstruct an interaction network.
Validated on GLV simulations (100 species, 100 samples, Erdos-Renyi and Barabasi-Albert networks); applied to Human Microbiome Project gut data, with a longitudinal check (121 individuals).

## What's relevant for my work
- Candidate keystones tend to form "keystone modules": neighboring species share similar EPI values, possibly one keystone plus "satellite" species -> supports looking at groups of species, not single ones.
- Network-free approach -> an alternative to centrality worth mentioning.
- Uses GLV simulations for validation, like my setup.

## Used for
Motivation (combinations / modules), related work.

## Limits
Presence-impact only; absence may just mean below detection limit; biased for very common/rare species (25-75% prevalence filter); modules not systematically identified. Code: MATLAB scripts in the supplement.
