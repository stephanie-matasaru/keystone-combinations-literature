# Identifying keystone species in microbial communities using deep learning
**Citation:** Wang2024DKI · **PDF:** not included (paywalled), https://doi.org/10.1038/s41559-023-02250-2
**Read:** publicly visible parts of the article page

## What it's about
DKI (data-driven keystone species identification) trains a deep learning model on microbiome samples from one habitat to learn its assembly rules, then estimates each species' keystoneness in a sample by simulating its removal. Validated on synthetic data and in vitro; applied to human gut (curatedMetagenomicData), oral, coral and soil microbiomes.

## What's relevant for my work
- Topological indices from correlation networks do not correlate with keystoneness -> supports "centrality fails".
- Keystoneness is community-specific: the same taxon can matter in one community and not another -> keystoneness should be evaluated per community.
- Code and data are public (github.com/spxuw/DKI).

## Used for
Related work, motivation, justification for weak centrality baselines.

## Limits
Single-species removal only; needs many samples to train. TODO: read the full text for validation details and limitations.
