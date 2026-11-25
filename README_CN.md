<p align="center">
  <a href="./README.md">English</a> | <strong>简体中文</strong>
</p>

<div align="center">

# Academic Research Skills（精简核心版）

**覆盖深度文献调研、系统综述筛选、学术论文撰写与模拟同行评审的多智能体科研 Skill 套件**

![Agent Skills](https://img.shields.io/badge/Agent_Skills-5_Core_Modules-6366f1?style=flat-square)
![License](https://img.shields.io/badge/License-See_LICENSE-10b981?style=flat-square)

</div>

---

## 项目概述

本仓库为 **Academic Research Skills** 多智能体科研技能套件的**精简最新核心版**：仅保留最新的五大核心 Skill、子智能体定义、命令规范、共享协议及文献适配器脚本，已移除历史变更日志、冗余多语种文档、历史审计归档与开发评测脚手架。

### 五大核心 Skill

| Skill 目录 | 核心定位 |
| :--- | :--- |
| `deep-research/` | 多源深度文献调研、苏格拉底式追问、信息源质量分级与 PRISMA / 预注册模板 |
| `sr-screener/` | 系统综述文献初筛与纳入/排除标准判定 |
| `academic-paper/` | 学术论文（IMRaD / 综述）结构规划、撰写、引文合规校验、双语摘要与图表设计（含 12 个专项子代理） |
| `academic-paper-reviewer/` | 多维度模拟审稿、锚定式论断核查与审稿意见修改辅导 |
| `academic-pipeline/` | 串联“调研 → 撰写 → 合规审计 → 审稿迭代”的端到端科研工作流 |

## 仓库结构

```text
academic-research-skills/
├── academic-paper/             # 论文写作 Skill、12 个专项 Agent、模板与写作参考
├── academic-paper-reviewer/    # 模拟同行评审 Skill 与锚定校验规范
├── academic-pipeline/          # 端到端科研流水线编排
├── deep-research/              # 深度文献调研、PRISMA 与信源质量体系
├── sr-screener/                # 系统综述筛选 Skill
├── agents/                     # 共享 Agent 定义
├── commands/                   # 快捷命令定义
├── shared/                     # 通用协议与合规工具
├── scripts/                    # 文献适配器（Zotero / Obsidian / 本地目录）与审计脚本
├── docs/                       # 核心使用文档
├── .claude-plugin/             # 插件清单（plugin.json / marketplace.json）
└── LICENSE, NOTICE.md, THIRD_PARTY.md, CITATION.cff
```

## 快速开始

可将本仓库整体作为 Claude Code / Codex 插件加载，或按需单独挂载单个 Skill 目录。详细模式与命令说明请查阅 [`QUICKSTART.md`](QUICKSTART.md) 与 [`MODE_REGISTRY.md`](MODE_REGISTRY.md)。

> 完整开源协议与上游归属声明保留在 [`LICENSE`](LICENSE)、[`NOTICE.md`](NOTICE.md) 与 [`THIRD_PARTY.md`](THIRD_PARTY.md)。
