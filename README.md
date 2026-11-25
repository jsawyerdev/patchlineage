# Patchlineage

> Status: concept repository - future work

Semantic analysis of upstream patches and their downstream impact.

## Objective

Explain the purpose of upstream software changes and locate equivalent or dependent code in downstream projects.

## Proposed scope

- Extract semantic intent from patches
- Map affected symbols and behaviour
- Find equivalent downstream implementations
- Track propagation and unresolved exposure

## Technical direction

Git, Tree-sitter, Clang, program analysis, and semantic dependency graphs.

The technologies above are candidates, not commitments. Selection will follow evidence from the smallest useful prototype.

## Open questions

- What observable result would make the first prototype useful?
- Which assumptions need controlled experiments before implementation?
- What independent oracle can determine whether an experiment succeeded?
- What is the smallest reproducible dataset or workload?

## Repository status

This repository reserves the project identity and records the initial concept. It contains no production implementation, published roadmap, or stable API.
