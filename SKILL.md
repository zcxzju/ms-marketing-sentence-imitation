---
name: ms-marketing-sentence-imitation
description: Acceptance-oriented sentence-and-structure imitation for Management Science Marketing theory manuscripts. Use when writing, rewriting, auditing, or outlining analytical marketing papers for the Management Science Marketing department; when the user asks to first identify the manuscript's MS Marketing topic class and then imitate same-topic MS Marketing articles paragraph by paragraph or sentence by sentence.
---

# MS Marketing Sentence Imitation

## Core Rule

Write like a Management Science Marketing theory paper, not like a proof package. Imitate reusable paper architecture, paragraph function, and sentence role; do not copy source-paper wording.

Never guarantee acceptance. Aim for an acceptance-oriented draft by making the marketing phenomenon real, the managerial decision explicit, the theoretical mechanism memorable, and the result order reviewer-friendly.

For imitation tasks, first classify the manuscript's topic class, then imitate same-class MS Marketing articles. Do not default to BlindBox/FOMO templates unless the manuscript's topic actually fits digital goods, stochastic products, social comparison, or retention.

## First Move

1. Inspect live artifacts before rewriting.
   - If the user gives a manuscript path, read section headings, abstract, introduction, model setup, propositions, figures, and result summaries.
   - If the user points to `/Users/chenxi/obsidian/MS_marketing`, list notes and PDFs there, search title fragments with `find` or `rg`, and prefer the user's notes over memory.
   - Translate abstract model objects into concrete marketing decisions, consumer states, constraints, and observable managerial diagnostics.

2. Classify the topic before choosing templates.
   - Read `references/topic-router-and-close-imitation.md` when the user asks for imitation, rewrite, positioning, introduction revision, or article-template selection.
   - Assign one primary topic class and, if needed, one secondary class.
   - Select local reference articles from the same class before using generic MS Marketing sentence templates.

3. Decide the imitation level.
   - Whole paper: use section architecture and result ordering.
   - Introduction: use the 8-paragraph MS Marketing introduction sequence.
   - Section rewrite: use paragraph function labels before drafting.
   - Sentence polish: imitate the sentence role, transition logic, clause order, and level of concreteness of same-class articles; do not reproduce their wording.

4. Keep the output manuscript-facing.
   - Lead with phenomenon, managerial puzzle, and mechanism.
   - Put equations after the economic object is named.
   - State propositions as design boundaries or comparative rules.
   - Move long derivations, tie cases, and exhaustive case splits to appendix language.

## Reference Files

Read only what the task needs:

- `references/topic-router-and-close-imitation.md`: use first for theme classification, reference-article selection, and sentence-by-sentence close imitation within the matched topic class.
- `references/section-architecture.md`: use for whole-paper outline, section ordering, result sequence, extensions, and assumption-discussion placement.
- `references/sentence-templates.md`: use for introduction paragraphs, contribution paragraphs, related-literature bridges, model-section prose, proposition lead-ins, and managerial implication sentences.

## Workflow

1. Diagnose the current draft in MS Marketing terms.
   - Which topic class does it belong to: pricing/dynamic demand, search/discovery, targeting/data, social influence/networks, platform/marketplace, digital goods/games, information design/persuasion, or welfare/regulation?
   - Is the first screen a real marketing practice?
   - Is the research question a firm/platform decision rather than a parameter exercise?
   - Is the behavioral or information primitive connected to a meaningful firm decision, consumer response, market outcome, or welfare implication?
   - Does every result answer a managerially named tradeoff?

2. Build a section-function map.
   - For each section or paragraph, assign one function: phenomenon, puzzle, research question, model primitive, benchmark, mechanism, optimal policy, welfare wedge, extension, assumption defense, or managerial diagnostic.
   - Delete or move text that has no function in the section.

3. Draft in sentence roles.
   - Start paragraphs with the role sentence, not a citation list or formula.
   - Use one paragraph for one move.
   - After technical statements, add one interpretive sentence that says what the condition means for marketing practice.

4. Audit for acceptance-facing risks.
   - Too technical before the puzzle is clear.
   - Purely mathematical novelty without marketing decision content.
   - Literature review written as a list instead of a sequence of gaps.
   - Results named by notation rather than design implications.
   - Extensions that look like a second paper instead of robustness or boundary conditions.

## Output Shapes

For a quick rewrite:

```text
Verdict:
Section function:
MS-style rewrite:
Why this is closer to Management Science Marketing:
```

For a full writing plan:

```text
1. Reference hierarchy
2. Target article structure
3. Introduction paragraph map
4. Section-by-section imitation map
5. Proposition/result order
6. Related-literature bridge sentences
7. Managerial implication diagnostics
8. What to move to appendix
```

For direct TeX edits, patch the manuscript and then run a compile check when the project has a known compile command.
