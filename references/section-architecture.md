# Section Architecture

Use this when outlining or restructuring an analytical/theory manuscript for Management Science Marketing.

## Target Shape

Default architecture:

```text
1. Introduction
2. Literature Review
3. Model / Baseline Environment
4. Main Mechanism and Consumer Behavior
5. Firm Optimization / Optimal Marketing Architecture
6. Profit, Consumer Surplus, and Welfare Implications
7. Extensions and Boundary Conditions
8. Discussion of Assumptions
9. Conclusion
```

Use a shorter architecture when the paper is compact:

```text
1. Introduction
2. Model
3. Analysis
4. Extensions
5. Conclusion
```

but preserve the same internal sequence: phenomenon -> puzzle -> primitive -> benchmark -> mechanism -> policy rule -> welfare/managerial boundary -> robustness.

## Reference Hierarchy from `/Users/chenxi/obsidian/MS_marketing`

Use these local notes/PDFs as style anchors:

- `The Joy of Shopping: Thrill of the Treasure Hunt`: best for opening a familiar consumption experience and turning it into a formal utility/design problem.
- `Pricing and Design of Pay-to-Win Add-Ons`: best for writing digital-game design, win/loss sensitivity, pricing, and counterintuitive product-design implications.
- `Searching for Rewards`: best for repeated purchase, loyalty, CRM, and history-conditioned consumer paths.
- `Retention or Acquisition? Behavior-Based Quality Disclosure`: best for two-period framing, retention-vs-acquisition titles, behavior-based disclosure, and customer relationship management.
- `Designing Information to Engage Customers`: best for information/exposure architecture and engagement incentives.
- `The Strength of Weak Commitments`: best for writing a weak-looking managerial tool as a strong strategic mechanism.
- `Limited Time Offer and Consumer Search`: best for whole-paper architecture: simple monopoly case, richer competition/dynamic setting, extensions, then assumption discussion.
- `Behavior-Based Pricing: Peer-Induced Fairness`: best for benchmark-first ordering and backward induction exposition.
- `Product Policy in Markets with Word-of-Mouth Communication`: best for decomposing a broad social force into distinct information functions.

## Introduction Architecture

Use eight paragraphs unless the journal format forces compression:

1. Broad but concrete phenomenon: common practice, market setting, and importance.
2. Specific practice and operational details: how firms/platforms actually implement it.
3. Managerial tension or puzzle: the practice is common, but its optimal design or profitability is unclear.
4. Research question: state the firm's decision and the questions the paper answers.
5. Modeling primitive: players, timing, information, consumer state, and key friction.
6. Main result: most memorable and counterintuitive finding.
7. Result depth: boundary condition, comparative static, welfare wedge, or managerial rule.
8. Contributions and roadmap: locate the paper in literature streams and preview structure.

## Model Section Architecture

Order the model section as:

1. Managerial object: what the firm chooses.
2. Consumer state: what consumers observe, remember, compare, or infer.
3. Timing: when state is realized and when the firm acts.
4. Utility or payoff primitives: define only after the economic role is clear.
5. Constraints: participation, incentive, feasibility, commitment, information, or common-price constraints.
6. Reduced problem: summarize what the model reduces to before solving.

For BlindBox, use this order:

```text
platform exposure architecture -> stochastic draw -> visible outcome history -> failed-consumer state -> follow-up eligibility -> common-price or targeted-price constraint -> firm profit
```

## Result Section Architecture

Use this sequence:

1. Benchmark result: what happens without the focal mechanism.
2. Consumer behavior result: how the focal mechanism changes willingness to pay or participation.
3. Firm policy result: optimal price, targeting, exposure, product design, or disclosure rule.
4. Profit comparison: why one architecture dominates another.
5. Welfare or consumer-surplus wedge: when firm-optimal and consumer-preferred policies diverge.
6. Boundary cases: when the mechanism weakens, disappears, or reverses.

## Extensions

Treat extensions as reviewer-risk management, not as a second main model.

Good extensions:

- One assumption changed at a time.
- Directly answers a likely referee concern.
- Produces the same managerial rule, a clear boundary, or a named exception.
- Keeps derivations in the appendix.

Weak extensions:

- Adds notation without changing paper insight.
- Competes with the main mechanism.
- Reads like robustness by exhaustion.
- Creates a new objective that is not connected to the introduction.

## Assumption Discussion

Separate extensions from assumption discussion.

Use assumption discussion for:

- Observability of prices or outcomes.
- Commitment to future price or follow-up access.
- Information visibility and exposure control.
- Consumer sophistication or bounded rationality.
- Platform implementation details.

Do not bury these defenses in proof paragraphs.
