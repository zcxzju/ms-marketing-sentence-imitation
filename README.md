# MS Marketing Sentence Imitation

[English](#english) | [中文](#中文)

## English

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

## 中文

一个用于撰写和修改 Management Science Marketing 部门解析建模/理论论文的 AgentSkill。

这个 skill 帮助 AI 写作代理在三个层级模仿 Management Science Marketing 文章的可复用写法：

- 整篇文章结构
- 段落功能
- 句子角色

它适合理论味较重的稿件，尤其是那些需要从“证明包”改成“可投稿营销论文”的草稿：先讲真实营销现象，再讲管理困惑，然后引入 formal model，并持续把技术结果翻译成审稿人容易记住的设计含义。

## 功能

使用这个 skill 可以：

- 改写 abstract、introduction、model section、result section 和 managerial implications；
- 把技术性 proposition 改写成面向 marketing reader 的设计边界；
- 将一篇 manuscript 映射到 Management Science Marketing 的文章结构；
- 诊断某一节是否读起来像 MS Marketing 理论文；
- 把抽象模型参数翻译成商业语言，尤其适用于 blind-box、FOMO、social comparison、retention、pricing 和 exposure-design 论文。

这个 skill 不承诺文章一定被接收。它提供的是一个更严格的写作流程，使文章更接近 Management Science Marketing 理论文的审稿期待和写作风格。

## 仓库结构

```text
.
|-- SKILL.md
`-- references
    |-- section-architecture.md
    `-- sentence-templates.md
```

`SKILL.md` 是入口文件，定义 skill 何时触发以及核心工作流。

`references/section-architecture.md` 包含整篇文章和章节层级的结构模板。

`references/sentence-templates.md` 包含 opening、puzzle、research question、literature gap、contribution、proposition、welfare 和 managerial implication 的句子角色模板。

## 安装

把这个仓库 clone 或复制到你的 Codex skills 目录：

```bash
cd ~/.codex/skills
git clone git@github.com:zcxzju/ms-marketing-sentence-imitation.git
```

然后重启或刷新 Codex，让 skill metadata 被重新加载。

## 示例 Prompt

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

## 设计原则

这个 skill 模仿的是结构、功能和修辞动作，不复制已发表论文的原文措辞。

推荐写作顺序是：

```text
phenomenon -> managerial puzzle -> model primitive -> benchmark -> mechanism -> policy rule -> welfare or managerial boundary -> robustness
```

对于 BlindBox 类型论文，这个 skill 会鼓励把符号翻译成 marketing objects：

- `\ell` -> exposure-adjusted comparison sensitivity
- visible outcomes -> exposure architecture
- follow-up choices -> retention architecture
- optimized regimes -> design boundaries
