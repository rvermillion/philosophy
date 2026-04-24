# Arrow's Theorem and the Fictive "I"

*Companion to narrator-weaver.md. This is the formal argument for why the weaving function is architecturally required, not merely pressure-selected.*

## Core claim

The weaving function / narrator / fictive "I" exists because **coherent group preferences provably don't exist**, and action requires something in their role. Arrow's impossibility theorem gives a formal reason why the unified "I" can't be an accurate aggregation of the coalition's preferences — it has to be a fiat construction, because accurate aggregation under reasonable fairness conditions is mathematically impossible.

This is a stronger architectural argument than the four-pressures version. The four pressures say *unified output is useful and selected for*. Arrow says *coherent group preference is formally non-existent*, so if downstream systems need something in that role, it has to be manufactured, not computed.

## The theorem, briefly

Arrow (1951): no aggregation rule takes individual preferences (complete, transitive) and produces a group preference (also complete, transitive) while satisfying:
- Unrestricted domain (works on any preferences)
- Non-dictatorship (no single individual's preferences determine the group's)
- Pareto efficiency (if everyone prefers A to B, group prefers A to B)
- Independence of irrelevant alternatives (group's A-vs-B preference depends only on individual A-vs-B preferences)

Something has to give. You can have aggregation, but something must violate.

## Application to coalition-of-parts

Games of Parts framework treats the agent as a coalition of parts with local preferences. Arrow applies: there is no well-defined "what the coalition wants" in the sense of complete, transitive ordering satisfying the fairness conditions. Group preference that action would require doesn't exist.

But action requires *something* in that role. You can't act on "the coalition is in a cycle over A, B, C." The architecture needs a mechanism producing a well-defined preference where none exists in the aggregation.

The "I" is that mechanism. The narrator doesn't *compute* the coalition's preference (doesn't exist). The narrator *declares* a preference on the coalition's behalf, and the declaration is what action runs on. The fiction isn't a lie about pre-existing preference — it's construction of something that didn't exist pre-declaration.

## Reframing the four pressures

The pressures aren't independent demands that happen to converge on "I." They're four downstream systems all requiring preference-like input:
- Action: needs a choice among alternatives
- Legibility: needs a modelable agent with goals
- Coherence-through-time: needs a consistent optimizer to track
- Compression: needs a single referent to compress to

All four presuppose a well-defined preference, which Arrow tells us the coalition cannot supply. The pressures converge on "I" because they're all consumers of the same non-existent thing. The weaving function is the organ that manufactures it.

## Arrovian violations map to failure modes of the "I"

Since Arrow's impossibility is conditional on rational aggregation, you dodge it by accepting one of the violations. Different violations correspond to different ways the "I" fails:

**Dictatorship**: one part dominates; "I" becomes that part's preference. Obsession, addiction, monomania — one coalition member has captured the narrator.

**Intransitivity**: "I" expresses cyclic preferences across contexts (A > B in one framing, B > C in another, C > A in a third). Matches observation that preferences are context-dependent and inconsistent under careful probing. Narrator smooths locally; cycles remain detectable over time.

**Independence violation**: "I"'s preference between A and B depends on irrelevant alternative C. Framing effects, decoy options, menu dependence — well-documented in behavioral economics, all evidence that "I" isn't a real preference but a construction inheriting the pathologies of the aggregation it's standing in for.

The fictive "I" accepts whichever Arrovian violation is cheapest in the current context. Mostly intransitivity smoothed by narrative consistency, with occasional dictatorship when one part captures the floor, with pervasive independence violations because the narrator is responsive to framing. Failures of the unified self map onto Arrovian violations — probably not coincidentally.

## Dissolution states reinterpreted

Arrow doesn't fail in meditation / psychedelics / dissociation — it becomes **visible**. The narrator's fiat weakens; what surfaces is the actual underlying aggregation problem: parts with local preferences, no coherent group preference, cycles and dictatorships becoming experientially detectable.

"Loss of self" = *loss of the Arrovian tie-breaker*. Parts still prefer things; no unified preference stands in for them. Which is why these states can be both liberating (tyranny of fictive unified preference loosens) and disorienting (thing action normally runs on isn't there).

## Implication for variant architectures

Arrow argument suggests the "I" isn't a human-specific architectural quirk. Any sufficiently complex agent with internal parts and external action requirements faces the same impossibility and needs the same kind of fiat.

The research question isn't "do LLMs have selves" but "**what Arrovian tie-breaker does an LLM's architecture implement, and how does its pattern of failures compare to the human pattern**." Different tie-breakers under different pressure configurations → characteristically different failure modes, different intransitivities, different susceptibilities to framing, different dictator-parts under stress.

Empirically tractable, not metaphysical.

## Connection to narrator-weaver

The narrator-weaver note describes the architecture; this describes why the architecture is required. The four pressures explain what demands the "I" satisfies; Arrow explains why those demands cannot be satisfied by accurate aggregation and therefore require fiat construction.

Together: the coalition has no coherent preference (Arrow). Downstream systems need a preference-like input (four pressures). The weaving function manufactures one by declaration (fictive "I"). The "I" fails in exactly the ways Arrovian violations would predict.

## Status

New thread. Integrates cleanly with Games of Parts, Nash equilibrium framing, compositional selfhood, narrator-weaver. Potentially the most *formally defensible* part of the framework — Arrow is a theorem, not a speculation. Worth developing carefully because it's the piece that could be presented to people who resist the more phenomenological or architectural arguments.

Possible extensions:
- Sen's subsequent work on Arrovian escapes (richer informational bases, interpersonal comparisons) and whether the narrator uses analogous moves
- Whether the narrator's fiat can be modeled as a specific social choice rule (approval voting? Borda? positional?) and what its characteristic violations would be
- Connection to bounded rationality: the narrator's fiat is a tractable substitute for an intractable aggregation, similar to how heuristics substitute for intractable optimization
