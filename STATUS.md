# STATUS

**Last updated:** 2026-06-13
**State:** First full draft written and built.
**Next action:** Do a prose/content pass on `main.tex`, with special attention to whether Section 4 stays illustrative rather than becoming an evidence burden.
**Blocker:** None.

## Working Thesis

Kinds and categories are best understood by their projectibility profiles: what they let us reliably infer, under which stabilizing conditions, for which explanatory or classificatory purposes, and with what failure modes. Homeostasis is one important stabilizing pattern, not the master criterion.

## Scope

This should be a synthetic position paper, not a full new theory paper. Its job is to make the mature view citable in one clean place by drawing together:

- the general correction in `../Not_Every_Stable_Cluster_Is_Homeostatic/`;
- the linguistic proof of concept in `../Definiteness_and_deitality/`;
- the methodological apparatus in `../Functions_as_Comparanda__Categories_as_Kinds__A_Homeostatic_Approach_to_Typology/`;
- the public-facing bridge from HPC vocabulary to profile language in `../Truth-Tracking_as_a_Homeostatic_Property_Cluster/`.

## Setup

- Created from the house-style LaTeX paper template on 2026-06-13.
- `references.bib` is a symlink to the central `.house-style/references.bib`.
- `.house-style/preamble.tex` and `.house-style/style-rules.yaml` are symlinks to the central house-style files.
- Use `references-local.bib` only for verified project-specific additions that do not belong in the central bibliography yet.

## Session Notes

### 2026-06-13

- Created `notes/section-plan.md` as a Roughdraft-reviewed plan before drafting.
- Revised the plan after review to treat projectibility-first as a methodological/explanatory order, define profiles as analytic specifications of worldly patterns, keep fields/practices as optional scope conditions, and make failure modes/demotion the main payoff after the thesis.
- Drafted `main.tex` into a compact 2,667-word position paper with six sections: introduction, profile package, projectibility priority, cross-level portability, failure modes/demotion, and conclusion.
- Added `references-local.bib` with a verified local entry for the current deitality paper title because the central bibliography still has an older subtitle for that item.
- Built successfully with `make`; final log scan showed no unresolved citation/reference warnings and no overfull/underfull boxes. Remaining style-script output is cadence warnings in definition-heavy paragraphs.
