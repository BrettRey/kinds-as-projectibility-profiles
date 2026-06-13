# Duplicate Review Board Synthesis

Date: 2026-06-13

Target: `main.tex`

Board design: complete duplication. The same six named standpoint seats were run once with Codex and once with Opus:

- Nelson Goodman - Projectibility Reviewer
- Richard Boyd - HPC Reviewer
- Matthew H. Slater - Stability Reviewer
- Muhammad Ali Khalidi - Network Reviewer
- Martin Haspelmath - Typology End-User
- Melanie Mitchell - AI and Truth-Tracking End-User

The external review Brett pasted during the run is treated as a separate input, not merged into either model set.

## Files

- Codex: `2026-06-13-codex-goodman.md`, `2026-06-13-codex-boyd.md`, `2026-06-13-codex-slater.md`, `2026-06-13-codex-khalidi.md`, `2026-06-13-codex-haspelmath.md`, `2026-06-13-codex-mitchell.md`
- Opus: `2026-06-13-opus-goodman.md`, `2026-06-13-opus-boyd.md`, `2026-06-13-opus-slater.md`, `2026-06-13-opus-khalidi.md`, `2026-06-13-opus-haspelmath.md`, `2026-06-13-opus-mitchell.md`

## Self-Check

The board converged strongly on "revise and resubmit" rather than acceptance or rejection. That convergence should be treated as a stress-test signal, not evidence of field consensus. The model sets differ in severity: Codex is shorter and more architecture-positive; Opus is sharper and more willing to press foundational problems. The external review is closer to an editor's targeted residual list than to a full referee report.

## Consensus Strengths

- The projectibility-first architecture is working. Both model sets repeatedly say the paper keeps projectibility as the epistemic payoff rather than burying it under mechanism talk.
- The stabilizer / maintainer / controller distinction is valuable. Reviewers treat it as a real disambiguation of overloaded `homeostatic` vocabulary.
- The demotion machinery is a distinctive contribution. Thin profile, wrong-level projection, decorative mechanism, over-homeostatization, and scope overreach all read as useful exit procedures.
- The decorative-mechanism test is the most exportable test. Several reviewers singled it out as the line that turns the framework into a usable discipline.

## Consensus Weaknesses

- The paper needs at least one worked micro-case. Codex and Opus both ask for a case that names the projection, diagnostics, support relation, stabilizer or absence of one, scope, and demotion condition.
- The order/stabilization distinction needs protection at the end. The external review flags the Section 6 tier list as silently merging the order axis with the stabilization axis; Slater and Khalidi reviewers independently press the same family of issues.
- `Stabilizer` still risks doing Q4 and Q5 work at once. Khalidi and Slater reviewers both object that the definition explains co-availability, which sounds structural/order-like, while the fifth question is modal/diachronic.
- Goodman remains underanswered. Codex asks for a worked contrast between a fitting profile and a projectible one; Opus presses the stronger grue/entrenchment problem and says "worldly order" alone doesn't solve it.
- The examples are too compressed for end users. Haspelmath wants an operational typology test; Mitchell wants an independent diagnostic for support routes in truth-tracking.

## Contradictions

- Goodman vs. everyone else: most reviewers accept that projectibility is foregrounded; Goodman says the hard Goodmanian problem is still avoided, not solved.
- Boyd vs. the strict-homeostasis move: Boyd worries that reserving `homeostatic` for controllers over-narrows the original HPC vocabulary; Slater and Khalidi generally like the anti-inflation move but want the axes separated more carefully.
- Slater vs. stronger-status language: Slater wants stable-but-mechanism-unknown profiles treated as full successes within scope; other seats often treat identified stabilizers as what makes the account stronger.
- End users vs. vocabulary note format: Haspelmath and Mitchell both like the vocabulary but want operational tests. That creates a budget tension: the paper can stay a compact vocabulary note only if it gives a micro-case rather than full applications.

## External Review Input

The external review says A-E are resolved but flags six residuals:

- Highest priority: Section 6 re-merges the order axis and stabilization axis.
- Boyd attribution in Section 3 is too strong; "in Boyd's later terms" should be checked, cut, or downgraded to "in broadly Boydian terms."
- The paper should declare that `kind` is used inclusively, while `natural kind` and `homeostatic` are stronger separable claims.
- Replace "measurement conventions" in Section 2 with "shared measurement standards" to avoid clashing with Section 4's "measurement design supplies the audit trail."
- The abstract should avoid making stabilizers sound like constituents of the profile.
- Confirm the acknowledgement string "Codex (GPT-5)."

## Prioritized Revision List

1. Fix Section 6's axis collapse.
   Replace the single ladder with a two-axis statement: one axis concerns structural order/non-accidentality; another concerns stabilization, with maintainer and controller as stronger subcases. Homeostasis is strict only on the stabilization/control axis.

2. Declare the inclusive sense of `kind` early.
   Add a sentence near the first definition: this paper uses `kind` inclusively for any projectibility profile; natural-kind and homeostatic claims are stronger, separable claims.

3. Clean up `stabilizer` and Q4/Q5 terminology.
   Consider reserving "ordering relation" for Q4 and "stabilizer" for Q5. Also allow a legitimate Q5 answer of robust stability without an identified separable stabilizer.

4. Downgrade or remove the Boyd programmatic/explanatory attribution.
   The sentence can become "In broadly Boydian terms..." or be cut. If kept as a specific attribution, verify against Boyd before shipping.

5. Add one worked micro-case.
   Best candidates: deitality for the paper's core linguistic payoff, or truth-tracking for the most operational contrast. The micro-case should show one prediction, one support relation, one failure/demotion condition, and what disappears if the stabilizer/mechanism is removed.

6. Make one end-user test runnable.
   For typology: define out-of-sample projection as held-out languages/families/constructions or new diagnostics. For AI: specify an independent diagnostic for the missing support route before testing retrieval, tools, or self-consistency.

7. Apply small wording fixes.
   Abstract: "records its diagnostics, the relations that stabilize it, its limits, and failure modes." Section 2: "shared measurement standards." Section 5: "stabilizers, where they exist and have been identified..." rather than making identification of a stabilizer a condition on full status.

## Bottom Line

The board's strongest signal is not that the paper is wrong. It is that the current draft has successfully exposed the right distinctions and now needs to prevent them from collapsing under its own summaries. The minimal next pass should fix the two-axis language, inclusive `kind` scope, stabilizer terminology, Boyd attribution, and abstract/measurement wording. The larger decision is whether to spend another paragraph on one worked micro-case; both model sets and both end-user seats say yes.
