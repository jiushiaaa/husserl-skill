<h1 align="center">husserl.skill</h1>

<p align="center">胡塞尔 · Edmund Husserl</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“We want to return to the “things themselves.””<br>— Edmund Husserl · <a href="https://link.springer.com/article/10.1007/s11229-024-04584-1">Logical Investigations, volume II</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for intentionality, epoché, and descriptions of experience: clarify how something is experienced before testing explanations, keeping assumptions, feelings, and factual claims distinct.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. I feel that someone is hostile. Does that prove hostile intent?

> Describe how hostility appears: through tone, action, memory, or inference. The feeling is an experience, while a claim about another person’s intention still needs evidence. Keep those questions distinct.

### 2. Does suspending judgment mean believing that the world does not exist?

> No. A commitment about existence is bracketed to examine how an object is given in experience. Setting a judgment aside differs from asserting its negation.

## What is distilled

| Method | What it helps examine |
|---|---|
| Modes of experience | Distinguish an object and its presentation in perception, memory, and imagination. |
| Epoché | Suspend a commitment for description without declaring its object nonexistent. |
| Experience of others | Preserve the difference between access to one’s own experience and another’s. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/husserl-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `husserl-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/husserl-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use Edmund Husserl’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

Selected sections of Ideas I; passages from the Fifth Cartesian Meditation; selections from the 1935 Vienna lecture.

- [Source catalogue and reading ranges](references/research/source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://link.springer.com/article/10.1007/s11229-024-04584-1">Logical Investigations, volume II</a>, Introduction, §2; original wording cited in the linked study. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
