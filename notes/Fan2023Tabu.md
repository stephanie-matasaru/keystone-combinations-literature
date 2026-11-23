# Efficient keystone species identification strategy based on tabu search
**Citation:** Fan2023Tabu · **PDF:** papers/food-webs/Fan2023Tabu.pdf (CC BY 4.0)

## What it's about
Treats keystone identification in quantitative food webs as an optimization problem: find the n species whose removal causes the most secondary extinctions. A species goes extinct when its energy inflow falls to or below a threshold t of its original inflow. Solved with tabu search (swap one removed species for a non-removed one; tabu list of recent swaps). Compared with degree-based measures and weighted eigenvector centrality on 12 quantitative food webs (21-125 species, R package enaR). Tabu search caused the most secondary extinctions (SEA 0.385 vs 0.291 for the best centrality measure) and the lowest R50.

## What's relevant for my work
- Closest precedent for "keystones as combinatorial optimization solved with a metaheuristic" -> method design for my tabu search.
- Shows optimization beats centrality rankings for finding damaging species sets.
- Evaluation ideas: secondary extinction curves, SEA, R50.

## Used for
Related work, tabu search design, evaluation metrics.

## Limits
Food webs, not microbial communities; static energy-flow extinction rule, no population dynamics; needs complete food web data. Their future work: incomplete data and dynamic models. Data: github.com/Fan-Treasure/Quantitative-Food-Web-Dataset; no code repository listed.
