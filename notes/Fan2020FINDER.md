# Finding key players in complex networks through deep reinforcement learning
**Citation:** Fan2020FINDER · **PDF:** not included (paywalled; not CC licensed), https://doi.org/10.1038/s42256-020-0177-2

## What it's about
FINDER is a deep reinforcement learning framework for finding key players: the set of nodes whose removal most degrades a network (NP-hard). Objective: accumulated normalized connectivity (ANC), i.e. the area under the curve of remaining connectivity vs fraction of nodes removed; tested with pairwise connectivity (critical node problem) and giant component size (network dismantling), with and without node removal costs. Uses a GraphSAGE-like encoder and a deep Q-network, trained on 200,000 small synthetic graphs (30-50 nodes), then applied to large real networks. Outperforms heuristics (HDA, CI, RatioCut, MinSum, GND and others) and is much faster on large networks.

## What's relevant for my work
- Shows "find the key player set" is a recognized NP-hard problem class -> framing.
- Train on small graphs, apply to large ones -> mirrors my small (exact) / large (scaling) evaluation design.
- ANC metric -> idea for scoring methods over all k at once (impact vs number removed).
- Strong modern baseline for set-of-nodes removal problems.
- Code: github.com/FFrankyy/FINDER (and Code Ocean capsule).

## Used for
Related work, problem framing, metric design, possible structural baseline.

## Limits
Objective is network connectivity (topology), not community dynamics, so it does not directly measure ecological impact.
