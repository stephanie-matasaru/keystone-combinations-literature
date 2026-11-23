# On good encodings for quantum annealer and digital optimization solvers
**Citation:** Ceselli2023Encodings · **PDF:** papers/quantum/Ceselli2023Encodings.pdf
**Read:** abstract and introduction excerpts

## What it's about
Studies how to encode constrained combinatorial problems as QUBOs. Benchmark: the cardinality constrained quadratic knapsack problem (one inequality and one equality / cardinality constraint), with four QUBO reformulations. Compares quantum annealing on D-Wave Advantage, probabilistic algorithms on digital hardware, and mathematical programming solvers. Finds that a linear penalization of the inequality improves on current best practice; also studies "sample persistence" (variables that keep the same value across annealing runs) for variable fixing.

## What's relevant for my work
- My problem has a cardinality constraint (exactly k species) -> how to encode it as a QUBO penalty matters for solution quality.
- Compares quantum and classical QUBO solvers on the same formulations -> model for my comparison.
- Related work they cite: annealers do well on small sparse instances but struggle on large or dense ones -> my QUBO will be dense.

## Used for
Quantum extension: constraint encoding, solver comparison design.

## Limits
Only instances that fit on the hardware; different problem (knapsack). TODO: read results section in full.
