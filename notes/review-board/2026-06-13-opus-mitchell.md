# Review — Melanie Mitchell seat (AI and Truth-Tracking End-User)

*Standpoint seat based on public work on analogy, robustness, and the gap between surface competence and reliable generalization. Not a claim about the actual person's views.*

**Source-grounding flag:** I have not read the cited companion papers (`reynolds2026truthTrackingProfiles`, `reynolds2025definitenessProjectibility`, `reynolds2025comparanda`, `reynolds2026notEveryStableCluster`). My review treats only the truth-tracking paragraph as it appears here. Any reference I make to the broader robustness/evaluation literature is flagged as needing verification.

## 1. One-sentence summary

A kind is a *projectibility profile* — a worldly property-and-relation pattern whose partial observation licenses specified inferences under specified conditions — and "homeostatic" should name only the demanding corrective-control subcase, not stability, network order, or maintenance in general.

## 2. Strengths

- **The "support routes" framing is exactly the right shape for AI evaluation.** Section 4's claim that "a large language model can participate strongly in some routes and weakly in others; surface improvement and truth-tracking improvement can come apart" names the distinction I most want a framework to enforce. Treating coherence, retrieval, tools, and error-correction as *different* routes (rather than as undifferentiated "capability") is the move benchmark-driven evaluation usually skips.

- **The decorative-mechanism / ablation test earns its keep.** "If removing the mechanism talk leaves the same predictions, the mechanism has not earned its place" (Section 3, recurring as failure mode 3) is ablation logic an ML reader already trusts. It's a genuine discipline, not a slogan, and it correctly keeps mechanism in service of projection rather than as a substitute for it.

- **Failure mode 5 (scope overreach) cashes out for AI.** "A model behavior projectible under benchmark conditions may not transfer to tool-using settings" is the benchmark-familiarity-vs-robust-generalization gap stated as a demotion rule. That the framework *can say no* — and ties saying-no to realism — is its most useful feature for failure analysis.

## 3. Weaknesses (specific and actionable)

- **The contrastive prediction is not operationalized and risks circularity.** Section 4 says self-consistency "should help where coherence is the missing support," and retrieval/tools "only when they strengthen the needed stabilizer." But the paper gives no *independent* diagnostic for which support is missing **before** you run the intervention. As written, you'd infer "coherence was the bottleneck" from the fact that self-consistency helped — which is the post-hoc reasoning this very paragraph warns against. Fix: supply one worked contrast — a task, two interventions, a predicted differential, and an independent way to label the bottleneck that doesn't read it off the result.

- **The attribution problem is named but not solved.** The routes (perception, testimony, coherence, measurement, intervention, error-correction, practical success) are asserted as a list and treated as roughly parallel, but for an LLM they aren't symmetric: retrieval and tools change the input/affordances, while self-consistency is a property of the model's own outputs. Crucially, a memorized benchmark answer and a genuine coherence-route success can produce *identical* surface output. The framework distinguishes them in principle but offers no behavioral test to separate them. Fix: add the attribution question explicitly to the profile package — "by which route did this success arrive, and what evidence discriminates routes?"

- **Demotion is stated abstractly with no metric for the AI case.** "Projectible under benchmark conditions may not transfer" is the right instinct, but what counts as *evidence* of demotion? Transfer-gap thresholds, distribution-shift tests, perturbation/robustness probes? The robustness literature has concrete protocols here *(claim about that literature — needs verification)*; connecting even one failure mode to a measurable transfer test would turn the taxonomy from a vocabulary into a usable instrument.

## 4. Key question at Q&A

For the truth-tracking profile, can you give an **independent diagnostic** for "the missing support route" — one that does not depend on whether the intervention helped — so the contrastive prediction is falsifiable rather than read off post hoc? Concretely: hand me a task where you predict, *in advance*, that retrieval helps and self-consistency doesn't, and tell me how you'd know you were wrong.

## 5. HPC-specific checks (as instructed)

- **Is projectibility the epistemic payoff?** Yes, cleanly and consistently. The projection target is primary throughout.
- **Do mechanisms explain projectibility rather than replace it?** Yes — this is the paper's strongest axis. The decorative-mechanism test actively enforces it.
- **Does the conclusion cash out in what the category lets readers predict/explain/generalize?** Only partially. The conclusion is a set of *questions*, which is honest, but an AI-evaluation reader leaves without a single fully worked predict-and-test instance. The truth-tracking case is the closest the paper comes, and it's underspecified — exactly the place where "does fluent success track the right support route?" should have been demonstrated, not gestured at.

## 6. Verdict

**Revise & Resubmit.** The support-routes-vs-surface-success distinction is genuinely useful for robustness and failure analysis, but the sole AI example is too thin and non-operational to show the framework buys predictive traction over existing evaluation vocabulary — fix the circularity and add one falsifiable contrast and it's an accept.

*I'm not smoothing toward consensus: my main objection (the truth-tracking prediction is not yet falsifiable) is independent of whatever the other seats weigh, and I'd hold R&R even if they lean accept.*
