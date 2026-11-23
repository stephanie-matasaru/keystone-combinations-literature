# Finding Key Nodes in Complex Networks Through Quantum Deep Reinforcement Learning
**Citation:** Xiong2025QDRL · **PDF:** papers/quantum/Xiong2025QDRL.pdf

## What it's about
Proof-of-concept quantum deep reinforcement learning for key node identification / network dismantling: a variational quantum graph neural network encoder with a parameterized quantum circuit as the Q-function (Double DQN). Reward = decrease in accumulated network connectivity (ANC) after removing a node, the same objective type as FINDER. Tested on synthetic (Erdos-Renyi, Watts-Strogatz) and empirical networks; the abstract claims it outperforms classical baselines with fewer parameters.

## What's relevant for my work
- Shows quantum methods being applied to key-node removal problems -> related work for the quantum chapter.
- Essentially a quantum counterpart of FINDER's approach.

## Used for
Related work (quantum approaches to key node problems).

## Limits
Proof-of-concept; advantages on large networks are expected only as hardware improves (not demonstrated); connectivity objective, not ecological. TODO: check results section for qubit counts and simulator vs hardware.
