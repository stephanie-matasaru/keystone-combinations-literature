# Structured interactions explain the absence of keystone species in synthetic microcosms
**Citation:** Mizrahi2025Structured · **PDF:** papers/microbiome/Mizrahi2025Structured.pdf (CC BY 4.0)

## What it's about
16 marine bacterial species assembled in 8 environments (different carbon sources). Each species was left out of the initial inoculation ("ecological knock-outs", EKOs). 115 of 128 EKOs caused no secondary impacts (extinctions or invasions); 12 caused one, and only one caused two. No keystone species in any environment.

A gLV model with random interactions (null model) predicted far more secondary impacts (max 4.4 +/- 3.0 per simulation set). Adding variation in carrying capacities (eq. 2-3) lowered this to 1.9 +/- 1.3, matching the experiments. Carrying-capacity variation creates structured ("hierarchical") interactions; specifically, "affected-based" correlations (a species inhibited similarly by all others) reduce secondary impacts. Interaction matrices inferred from the data and spent-media experiments both showed this structure.

## What's relevant for my work
- Experimental evidence that single keystones are rare -> motivates searching for combinations.
- Random-interaction gLV communities overestimate keystone effects -> my synthetic communities should include carrying-capacity variation; random vs structured can be an experimental factor.
- Metrics to reuse: number of secondary impacts (extinctions + invasions), distance from the full community.
- Open question: they test single removals only; do combinations break this resilience?

## Used for
Synthetic data generation, evaluation metrics, motivation, discussion.

## Limits
Marine bacteria, not gut; 16 species; species removed at assembly (drop-out), not from an established community; sampled after 7 growth-dilution cycles, so stable states are not guaranteed. Data: amplicon sequencing on NCBI SRA (PRJNA1320718).
