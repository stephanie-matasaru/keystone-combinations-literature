# Towards Robust Benchmarking of Quantum Optimization Algorithms
**Citation:** Bucher2024Benchmarking · **PDF:** papers/quantum/Bucher2024Benchmarking.pdf (arXiv preprint)

## What it's about
Guidelines for fair benchmarking of quantum vs classical optimization: (1) choose state-of-the-art solvers on both sides and give each its best formulation, plus a naive baseline; (2) use diverse, reproducible, non-cherry-picked instances; (3) use a holistic metric balancing time and quality (time-to-solution, best solution within a time limit, Pareto front); (4) give all methods equal hyperparameter tuning effort. Case studies on Max-Cut and TSP with QAOA (simulated), D-Wave, simulated annealing, tabu search, Gurobi, CPLEX.

## What's relevant for my work
- Checklist for designing a fair comparison between my QUBO/quantum solvers and tabu/GA/SA.
- Their results: no quantum advantage; simulated annealing was best on small random instances, branch-and-cut on larger real-world-style ones; D-Wave's embedding overhead hurt total time -> realistic expectations.
- XY-mixer was the best QAOA variant for permutation constraints -> relevant if I try QAOA with an exactly-k constraint.

## Used for
Experimental design of the quantum vs classical comparison, metrics.

## Limits
Preprint; only two problem types; QAOA timings are estimated, not measured on hardware.
