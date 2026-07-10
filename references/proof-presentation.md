# Proof Presentation for MS / Marketing Science Journals

Use this when the manuscript contains analytical proofs, propositions, lemmas, or theorems. These rules govern what stays in the main text versus the appendix, how to present results at journal level, and how to handle results that resist closed-form solutions.

## Main Text vs Appendix Discipline

**Main text should contain:**
- The proposition/theorem statement (clear, self-contained, with all assumptions named)
- One-sentence economic intuition before the formal statement
- One-sentence economic interpretation after the formal statement
- Critical proof steps that carry economic meaning (e.g., which constraint binds, which term drives the sign)
- Comparative statics results with economic interpretation
- The key inequality or cutoff that separates policy regimes

**Move to appendix:**
- Routine algebraic manipulations
- Case splits that verify boundary conditions
- Second-order condition verification (unless the SOC itself carries economic meaning)
- Existence/uniqueness proofs that use standard techniques
- Any derivation longer than 6 lines of pure algebra
- Tie-breaking cases where one policy weakly dominates another

## Proposition Style

**Before the proposition:**
```text
The next result identifies the design boundary between [policy A] and [policy B].
```

**The proposition itself:**
- State all assumptions explicitly (do not say "under the model above" — restate the key conditions)
- Use economic language, not just mathematical notation
- Name the cutoff or regime condition in words: "when comparison pressure exceeds a threshold, ..."

**After the proposition:**
```text
Economically, the condition says that [plain-language meaning].
The mechanism is [one sentence].
This is why [apparently weaker policy] can outperform [apparently stronger policy].
```

## Sufficient-Condition Protocol

When a result does not admit a closed-form solution:

1. **Do not force a bad algebraic derivation.** State the result qualitatively with a sufficient condition.
2. **Provide a sufficient condition** that makes the qualitative claim hold, even if it is stronger than necessary.
3. **Label the sufficient condition clearly** so the reader knows it is not tight.
4. **In a Remark**, explain that the qualitative pattern is robust beyond the sufficient condition, and sketch why (monotonicity, continuity, boundary behavior).
5. **Never** present a numerical example as proof of a general claim. Numerical examples belong in a remark or footnote, labeled as "illustrative."

**Example structure:**
```text
Proposition X. Under condition [sufficient condition], the optimal policy
exhibits [qualitative pattern].

Proof. [Analytical argument using the sufficient condition.]

Remark. When [sufficient condition] is relaxed, the qualitative pattern
persists because [monotonicity/continuity argument]. We provide the
full characterization in Appendix Section Y.
```

## Lemma and Corollary Discipline

- **Lemma**: use only for intermediate results that are reused in multiple propositions. A lemma used exactly once should be absorbed into the proposition's proof.
- **Corollary**: reserve for direct logical consequences of a proposition (same assumptions, weaker conclusion). Do not use a corollary to introduce new assumptions or a different model variant.
- **Remark**: use for qualitative extensions, T>2 horizon generalizations, parameter-limit behavior, and robustness claims that go beyond the proposition's formal scope.

## Benchmark Extensions (Fixed-Reference, No-FOMO, etc.)

- In the main text, state the benchmark result in **~5 lines maximum**: the benchmark's optimal policy, profit, and how it differs from the main model.
- Full derivation of the benchmark's optimal policy, FOCs, SOCs, and case analysis go in the appendix.
- Frame the benchmark as "what happens without [focal mechanism]" — not as a separate paper.

## Plagiarism Safety Rule

After any sentence-level imitation, verify that no passage contains 7+ consecutive words identical to any source paper. If found, rewrite the passage while preserving the sentence role and logical structure.

## Self-Check for Proof-Heavy Sections

Before finalizing, verify:
1. Every proposition has a one-sentence economic interpretation after the formal statement.
2. No proof in the main text exceeds 6 lines of pure algebra.
3. Every assumption used in a proof is either in the proposition statement or in a clearly named lemma.
4. Results that lack closed-form solutions are handled via sufficient conditions + Remark, not forced algebra.
5. Corollaries do not introduce new assumptions; new-assumption variants go in Remarks or separate Propositions.
6. Benchmark derivations are brief in main text, complete in appendix.
