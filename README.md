# MS Marketing Sentence Imitation

An AgentSkill for writing and revising analytical marketing theory manuscripts in a Management Science Marketing style.

The skill helps an AI writing agent imitate the reusable structure of Management Science Marketing articles at three levels:

- whole-paper architecture
- paragraph function
- sentence role

It is designed for theory-heavy manuscripts where the draft needs to read less like a proof package and more like a publishable marketing paper: concrete phenomenon first, managerial puzzle second, formal model third, and memorable design implications throughout.

## What It Does

Use this skill to:

- rewrite abstracts, introductions, model sections, result sections, and managerial implications;
- turn technical propositions into marketing-facing design boundaries;
- map a manuscript onto a Management Science Marketing article structure;
- diagnose whether a section reads like an acceptance-oriented marketing theory paper;
- translate abstract model primitives into business language, especially for blind-box, FOMO, social comparison, retention, pricing, and exposure-design papers.

The skill does not promise journal acceptance. It gives the agent a stricter writing workflow aimed at the standards and style of Management Science Marketing theory articles.

## Repository Structure

```text
.
|-- SKILL.md
`-- references
    |-- section-architecture.md
    `-- sentence-templates.md
```

`SKILL.md` is the entry point. It defines when the skill should trigger and the core workflow.

`references/section-architecture.md` contains whole-paper and section-level structures.

`references/sentence-templates.md` contains sentence-role templates for openings, puzzles, research questions, literature gaps, contributions, propositions, welfare, and managerial implications.

## Installation

Clone or copy this folder into your Codex skills directory:

```bash
cd ~/.codex/skills
git clone git@github.com:zcxzju/ms-marketing-sentence-imitation.git
```

Then restart or refresh Codex so the skill metadata is loaded.

## Example Prompts

```text
Use ms-marketing-sentence-imitation to rewrite my introduction for Management Science Marketing.
```

```text
Audit this Analysis section and tell me whether it reads like an MS Marketing theory paper.
```

```text
Imitate Management Science Marketing article structure paragraph by paragraph for this BlindBox manuscript.
```

```text
Turn these propositions into reader-friendly marketing design rules.
```

## Design Principle

The skill imitates structure, function, and rhetorical moves. It should not copy wording from published papers.

The preferred writing order is:

```text
phenomenon -> managerial puzzle -> model primitive -> benchmark -> mechanism -> policy rule -> welfare or managerial boundary -> robustness
```

For BlindBox-style papers, the skill encourages translating notation into marketing objects:

- `\ell` -> exposure-adjusted comparison sensitivity
- visible outcomes -> exposure architecture
- follow-up choices -> retention architecture
- optimized regimes -> design boundaries
