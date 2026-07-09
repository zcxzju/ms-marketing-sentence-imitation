# Sentence Templates

Use these as sentence-role templates. Replace bracketed text with manuscript-specific content. Do not copy article wording from reference papers.

## Opening Phenomenon

Purpose: make the paper look like it starts from a real marketing practice.

Patterns:

- `[Firms/platforms/retailers] increasingly use [marketing tool] to [managerial objective].`
- `In markets such as [examples], consumers often [observable behavior] after [trigger/event].`
- `[Marketing practice] is not merely a pricing tactic; it changes [consumer path/state/information environment].`
- `These practices are economically important because they shape [repeat purchase/search/engagement/retention/welfare].`

Avoid:

- Starting with notation.
- Starting with a generic sentence about uncertainty.
- Starting with "we study" before the phenomenon is concrete.

## Puzzle and Tension

Purpose: turn the phenomenon into a publishable management problem.

Patterns:

- `Although [practice] appears to [obvious benefit], it can also [strategic cost].`
- `The key challenge is that [same tool] simultaneously [benefit] and [cost].`
- `This creates a design problem: should the firm [policy A], or should it [policy B]?`
- `The answer is not obvious because [consumer state/constraint/information] changes with [firm action].`
- `A policy that expands reach may lower profit if it pools [strong state] with [weak state] under a common [price/message/disclosure].`

For BlindBox:

- `Public outcome visibility appears to be a natural retention device, but it also determines which failed consumers share the follow-up pricing pool.`
- `The managerial object is not visibility per se, but the set of post-draw histories that visibility keeps commercially active.`

## Research Question

Purpose: state the firm-side decision clearly.

Patterns:

- `We ask when a firm should [broad design] rather than [targeted design].`
- `The paper studies how [firm-controlled architecture] changes [consumer state] and, in turn, [pricing/retention/welfare].`
- `We take the [firm/platform]'s perspective and ask three questions: how does [primitive] affect [behavior], when does [policy] dominate [policy], and what are the welfare implications?`
- `To answer these questions, we build a model in which [consumer state] links [marketing action] to [firm objective].`

## Literature Gap

Purpose: avoid a list of citations; make each literature stream do one job.

Patterns:

- `Prior work on [stream] explains [known mechanism]. We add [missing state/action] by allowing [firm/customer] to [new behavior].`
- `This literature typically treats [object] as [old role]. In our setting, [object] becomes [new role].`
- `The closest papers study [A]. We differ by focusing on [B], where [why B matters].`
- `Our contribution is not that [broad phenomenon] matters, but that [specific mechanism] changes [managerial decision].`

Three-stream structure for BlindBox-like papers:

1. Probabilistic selling / loot-box design: add public outcome histories and repeat purchase.
2. Social comparison / peer exposure / FOMO: comparison exposure is not a uniform demand shifter.
3. Dynamic purchasing / targeting / retention: the state is relative outcome history, not only purchase history.

## Contribution Paragraphs

Purpose: divide contributions by role.

Patterns:

- `The first contribution is modeling: we introduce [primitive] into [marketing decision].`
- `The second contribution is theoretical: we show that [intuitive policy] can be dominated by [counterintuitive policy] when [condition].`
- `The third contribution is managerial: the model yields a diagnostic rule based on [observable pattern].`
- `This distinction matters because [observable state] determines whether the firm should [policy A] or [policy B].`

Use "contribution" only after the phenomenon, puzzle, and result are already understandable.

## Model Section Prose

Purpose: make formal setup readable before equations.

Patterns:

- `The model has three ingredients: [consumer state], [firm action], and [constraint/mechanism].`
- `The firm chooses [decision] after observing/committing to [information].`
- `Consumers differ not in [irrelevant trait], but in [state created by the marketing environment].`
- `[Parameter] captures [marketing meaning]. It matters because it shifts [binding constraint/participation condition].`
- `The firm's problem is therefore to trade off [reach] against [state-specific willingness to pay].`

For `\ell`:

- `The parameter \ell is an exposure-adjusted comparison-sensitivity primitive. It summarizes how strongly a consumer reacts when the platform makes a self-lacks-H / peer-has-H comparison salient.`
- `\ell matters because it changes which follow-up constraint binds.`

## Proposition Lead-Ins

Purpose: make results memorable before the theorem statement.

Patterns:

- `The next result identifies the design boundary between [policy A] and [policy B].`
- `The proposition shows that the firm should not simply maximize [visibility/reach/engagement].`
- `The result has a simple interpretation: [policy A] works when [state], whereas [policy B] works when [state].`
- `The cutoff is useful because it converts an abstract comparison effect into a managerially observable regime.`

After proposition:

- `Economically, the condition says that [plain-language meaning].`
- `The mechanism is [one sentence].`
- `This is why [apparently weaker policy] can outperform [apparently stronger policy].`

## Welfare and Managerial Implications

Purpose: convert model results into publication-facing implications.

Patterns:

- `The firm-optimal policy need not maximize consumer surplus because [profit mechanism] and [consumer value] load on different histories.`
- `The model therefore predicts a wedge between [private design incentive] and [consumer/welfare outcome].`
- `Managers should measure [observable behavior] rather than average demand alone.`
- `When [observable pattern], the model recommends [policy]. When [opposite pattern], it recommends [alternative policy].`

BlindBox diagnostic table rows:

```text
Observable pattern -> Interpretation -> Recommended design
repeat purchases after both failed-together and behind-peer histories -> broad engagement remains active -> preserve broad follow-up
repeat purchases mainly after observed peer success -> catch-up urgency dominates -> use smaller peer groups or targeted offers
broad exposure lowers repeat purchase -> common-price bottleneck -> segment exposure
late-campaign spikes after visible winners -> deadline-based catch-up -> use countdowns and limited coupons
```

## Acceptance-Facing Rewrite Checklist

Before finalizing, check:

- The first paragraph names a real marketing practice.
- The puzzle appears before the model.
- The firm decision is stated as a marketing design choice.
- The main result can be remembered without notation.
- Each proposition has a one-sentence economic interpretation.
- Related literature ends each stream with a "we differ because" sentence.
- Extensions answer referee concerns and do not crowd the main result.
- The conclusion returns to managerial diagnostics rather than proof details.
