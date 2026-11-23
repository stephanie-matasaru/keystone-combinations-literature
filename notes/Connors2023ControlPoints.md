# Control points for design of taxonomic composition in synthetic human gut communities
**Citation:** Connors2023ControlPoints · **PDF:** papers/microbiome/Connors2023ControlPoints.pdf (CC BY 4.0)

## What it's about
A 10-species synthetic human gut community. Two-stage approach to control its composition: (1) model-guided tuning of media components, (2) tuning initial inoculum densities. A gLV model (L1-regularized) was fitted and outperformed a logistic (CSLE) model and a shuffled-interaction gLV null model. The gLV model was then used to simulate all 2- to 9-member subsets and select communities with low (or high) composition variability across passages; designs were tested experimentally.

## What's relevant for my work
- Uses a gLV model to search over species subsets and pick the best ones by an objective -> closest real-data example of subset selection with gLV.
- gLV predicted held-out 10-member data well (Pearson rho = 0.92), but small subsets (2-4 members) only moderately (rho = 0.55) -> evidence for how far gLV predictions can be trusted.
- Shuffled-interaction gLV as a null model -> evaluation idea.

## Used for
Related work (subset design with gLV), justification for using gLV, limitations.

## Limits
Single 10-member community; batch culture endpoints are not necessarily steady states; some species often mispredicted.
