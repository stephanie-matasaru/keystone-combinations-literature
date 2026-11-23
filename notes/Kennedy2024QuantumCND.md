# Network Vulnerability Analysis via Quantum Computing
**Citation:** Kennedy2024QuantumCND · **PDF:** not included (free accepted manuscript on NSF PAR: https://par.nsf.gov/servlets/purl/10561993)

## What it's about
Formulates the k-Critical Node Detection problem (choose k nodes whose removal minimizes pairwise connectivity) as QUBOs for quantum annealing. Proposes a new ILP formulation and its QUBO (QUBO2), which needs fewer variables and qubits than the standard one. Tested with a D-Wave quantum annealer, D-Wave's hybrid solver and classical simulated annealing, against CPLEX (exact), greedy and random, on small random graphs (up to 15 vertices).

## What's relevant for my work
- Direct template for writing "choose k nodes to remove" as a QUBO, including the cardinality constraint.
- Honest results: quantum methods did not beat classical greedy at 15 vertices; hybrid sometimes matched greedy; the QPU could not embed ~20-vertex instances; some solutions violated the "exactly k" constraint.
- Practical issues to expect: penalty scaling, chain breaks, embedding limits.

## Used for
Quantum extension: QUBO formulation, solver setup, expected limitations.

## Limits
Very small graphs; 5 graphs per setting; connectivity objective, not ecological; no quantum advantage shown.
