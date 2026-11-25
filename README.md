<p align="center">
  <strong>English</strong> | <a href="./README_CN.md">简体中文</a>
</p>

<div align="center">

# Academic Research Skills（Curated Core Edition）

**End-to-End Multi-Agent Skill Suite for Deep Literature Research, Systematic Screening, Academic Paper Writing, and Peer Review**

![Agent Skills](https://img.shields.io/badge/Agent_Skills-5_Core_Modules-6366f1?style=flat-square)
![License](https://img.shields.io/badge/License-See_LICENSE-10b981?style=flat-square)

</div>

---

## Overview

A streamlined, up-to-date edition of the **Academic Research Skills** multi-agent suite, retaining only the latest core skills, agents, commands, shared references, and verification scripts while stripping legacy changelogs, historical audit dumps, eval harnesses, and extra locale files.

### Five Core Skills

| Skill Directory | Purpose |
| :--- | :--- |
| `deep-research/` | Multi-source literature discovery, Socratic questioning, source quality hierarchy, PRISMA / preregistration templates |
| `sr-screener/` | Structured systematic-review screening and inclusion/exclusion triage |
| `academic-paper/` | Guided IMRaD & survey paper drafting, citation compliance, bilingual abstract writing, structure & visualization agents |
| `academic-paper-reviewer/` | Multi-dimensional peer-review simulation, anchored claim checks, and revision coaching |
| `academic-pipeline/` | End-to-end orchestration connecting literature search, drafting, compliance auditing, and review |

## Repository Structure

```text
academic-research-skills/
├── academic-paper/             # Paper writing skill, 12 specialized agents, templates & references
├── academic-paper-reviewer/    # Peer review skill & anchored verification rules
├── academic-pipeline/          # End-to-end research-to-submission orchestration
├── deep-research/              # Literature search, PRISMA & source-quality frameworks
├── sr-screener/                # Systematic review screening skill
├── agents/                     # Shared agent definitions
├── commands/                   # Slash command specifications
├── shared/                     # Common protocols & compliance utilities
├── scripts/                    # Literature adapters (Zotero/Obsidian/Folder) & audit scripts
├── docs/                       # Core documentation
├── .claude-plugin/             # Plugin manifest (plugin.json / marketplace.json)
└── LICENSE, NOTICE.md, THIRD_PARTY.md, CITATION.cff
```

## Quick Start

Mount this repository as a Claude Code / Codex plugin or load individual skill folders (`deep-research/`, `academic-paper/`, `academic-paper-reviewer/`, `academic-pipeline/`, `sr-screener/`). See [`QUICKSTART.md`](QUICKSTART.md) and [`MODE_REGISTRY.md`](MODE_REGISTRY.md) for detailed mode and command usage.

> Upstream attribution and third-party licenses are preserved in [`LICENSE`](LICENSE), [`NOTICE.md`](NOTICE.md), and [`THIRD_PARTY.md`](THIRD_PARTY.md).
