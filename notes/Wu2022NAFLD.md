# Targeting keystone species helps restore the dysbiosis of butyrate-producing bacteria in nonalcoholic fatty liver disease
**Citation:** Wu2022NAFLD · **PDF:** papers/microbiome/Wu2022NAFLD.pdf

## What it's about
Identifies keystone gut species in NASH/NAFLD. Pipeline: SparCC co-occurrence network -> causal inference with a gLV model -> HITS hub scores -> dynamic intervention simulation (perturbing each species in the gLV model) -> iterative feature elimination (IFE) to pick the species combination with the highest combination intervention score (CIS).
Discovery cohort: 16 healthy, 25 obese, 22 NASH adolescents (16S). Validation cohort: 31 healthy, 14 NAFLD, 24 NAFLD-cirrhosis adults.
Result: 8 keystone species for NASH (CIS 0.923, the "92.3% recovery"); 11 for obesity (CIS 0.903).

## What's relevant for my work
- One of the few papers that already selects a combination of species, using a step-by-step greedy-like method (IFE) -> direct baseline.
- HITS centrality -> another centrality baseline.
- Keystone species were not the most abundant or most changed taxa.
- Code: github.com/tjcadd2020/NAFLD_keystone; processed data in NODE (OEZ013156).

## Used for
Baselines (IFE, HITS), related work, application/motivation (medical use).

## Limits
Networks inferred from cross-sectional data, so results depend on model assumptions; interventions are simulated, not tested; small discovery cohort; cohorts differ in age and sequencing platform.
