# STATUS

**Last updated:** 2026-06-13
**State:** Post-review revision pass drafted and built.
**Next action:** Final diff check, commit, push, and reopen `main.pdf`.
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
- Added `README.md` and CC BY 4.0 `LICENSE` for the public GitHub repository.
- Revised `main.tex` after follow-up review: reserved `profile` for the worldly property-and-relation pattern, moved diagnostics/stabilizers/failure modes into the profile specification, narrowed `stabilizer`, clarified the Q3/Q4 split, promoted the decorative-mechanism test into Section 3, made the truth-tracking example prediction-first, and added the regulative-contribution/constitutive-thesis caveat.
- Web-checked Boyd 1999 pagination. PhilPapers, Stanford Encyclopedia, Springer references, and other indexed bibliographies mostly give pp. 141--185; a ResearchGate draft/listing gives 141--186. The central `references.bib` entry was corrected later in this session.
- Reread the four portfolio anchor papers one by one and checked the external load-bearing sources via local source notes/text. Source-grounded fixes: credited Slater's stability as already projectibility-shaped, added Boyd's programmatic/explanatory definition distinction, added a Khalidi guardrail for non-causal extensions of network order, separated typological measurement design from actual stabilizers, and sharpened the truth-tracking route-specific prediction.
- Rebuilt and opened `main.pdf`; log scan showed no unresolved citation/reference warnings and no overfull/underfull boxes. Remaining LaTeX warnings are the known `fancyhdr`/`microtype` preamble warnings; style checker reports only two cadence warnings.
- Ran complete duplicate review board: six named standpoint seats with Codex and the same six with Opus. Outputs and synthesis are in `notes/review-board/`. Main signal: the architecture works, but the next pass should protect the order/stabilization distinction, clarify `kind` scope, clean up stabilizer terminology, and add or defer a worked micro-case.
- Completed the follow-up revision pass: declared inclusive `kind`, split Q4 ordering from Q5 stabilization, removed evidential order as a worldly ordering relation, allowed robust stability without an identified separable stabilizer, added a compact truth-tracking evaluation micro-case, rewrote the conclusion around two axes, downgraded the Boyd attribution to "broadly Boydian", and made the AI acknowledgement less version-specific. Also corrected central `boyd1999` pagination to 141--185 after web verification.
