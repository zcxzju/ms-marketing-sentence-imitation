---
name: ms-mkt-publish
description: Acceptance-oriented Chinese-output sentence-and-structure imitation for Management Science / Marketing Science analytical manuscripts. Use when writing, rewriting, auditing, or outlining analytical marketing papers; classify topic + method, compare same-topic articles, then imitate paragraph-by-paragraph or sentence-by-sentence.
---

# MS MKT Publish

## Core Rule

Default to Chinese output. Keep article titles, journal names, variables, equations, and technical terms in English when translation would reduce precision.

Write like a top marketing journal theory paper, not like a proof package. Imitate reusable architecture, paragraph function, and sentence role; never copy source-paper wording.

Never guarantee acceptance. For imitation tasks, first classify the manuscript's topic class, then imitate same-class articles. Do not default to BlindBox/FOMO templates unless the manuscript's topic actually fits.

## Mandatory First Move

For any substantive audit, rewrite, outline, or imitation task, start with the **positioning benchmark**:

```text
定位基准：
1. 研究对象 / 主题类别：
2. 本文使用的方法：
3. 最接近的同主题可比文章：
4. 这些可比文章使用的方法：
5. 这些可比文章的主要结论：
6. 与本文相比，哪些维度更强 / 更弱：
对写作 / 改写的含义：
```

When there are at least two comparables or the user asks for a visual, include a compact Chinese Mermaid mind map after the benchmark.

## Workflow

1. **Build the positioning benchmark** — classify topic, method, find comparables, compare dimension-by-dimension. Read `references/topic-router-and-close-imitation.md` for classification rules and close imitation protocol.

2. **Build a section-function map** — assign one function per section/paragraph (phenomenon, puzzle, research question, benchmark, mechanism, optimal policy, welfare wedge, extension, assumption defense, managerial diagnostic). Delete or move text that has no function.

3. **Draft in sentence roles** — start each paragraph with the role sentence, not a citation list or formula. One paragraph = one move. After technical statements, add one interpretive sentence that says what the condition means for marketing practice.

4. **Audit for acceptance-facing risks** — too technical before the puzzle is clear; purely mathematical novelty without marketing decision content; literature review as a list instead of gaps; results named by notation rather than design implications; extensions that look like a second paper.

5. **Proof-presentation audit** — if the manuscript contains proofs, read `references/proof-presentation.md` for rules on what stays in main text vs appendix, how to handle unclosed-form results, and how to present propositions at MS/MKT journal level.

## Output Shapes

Quick rewrite:

```text
定位基准：（六项）
段落 / 小节功能：
MS-style 改写：
为什么这更接近目标期刊风格：
```

Full writing plan (12 items):

```text
1. 研究对象与主题分类
2. 方法分类
3. 同主题可比文章表
4. 主题-方法-可比文章思维导图
5. 参考文章层级
6. 目标文章结构
7. 引言段落地图
8. 逐节模仿地图
9. 命题 / 结果顺序
10. 相关文献桥接句
11. 管理启示诊断
12. 应该移到 appendix 的内容
```

For direct TeX edits, patch the manuscript and run a compile check when the project has a known compile command.

## Reference Files

Read only what the task needs:

- `references/topic-router-and-close-imitation.md`: topic classification, reference selection, sentence-by-sentence close imitation.
- `references/section-architecture.md`: whole-paper outline, section ordering, result sequence, extensions placement.
- `references/sentence-templates.md`: introduction, contribution, model prose, proposition lead-ins, managerial implications.
- `references/proof-presentation.md`: proof placement, proposition style, sufficient-condition protocol, appendix discipline.
