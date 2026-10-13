<h1 align="center">husserl.skill</h1>

<p align="center">胡塞尔 · Edmund Husserl</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“我们要回到“事情本身”。”<br>— 胡塞尔 · <a href="https://link.springer.com/article/10.1007/s11229-024-04584-1">《逻辑研究》第二卷</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将意向性、悬置与经验描述整理为思想分析 Skill，让 AI 先说明事物怎样被经验到，再检验解释，避免把预设、感受和事实断言混在一起。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 我感到有人敌视我，是否就能证明对方真的有敌意？

> 先描述敌意是怎样出现的：语气、动作、回忆还是推测。被敌视的感受可以是真实经验，但关于他人意图的判断仍需要证据；描述与判断各有位置。

### 2. 悬置判断，就是认为世界不存在吗？

> 不是。这里暂缓的是对存在的直接承诺，以便考察经验怎样给予对象。把判断放在一旁与否认判断内容，是不同的操作。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 经验方式 | 区分感知、回忆、想象中的对象及其呈现方式。 |
| 悬置 | 暂缓一个存在判断，专注描述，而非宣布对象不存在。 |
| 他者经验 | 尊重他人与自身经验进入方式的差别。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/husserl-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `husserl-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/husserl-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：**“用胡塞尔的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

《观念 I》相关节选；《笛卡尔式沉思》第五沉思选段；1935 年维也纳讲演选段。

- [原作来源、版本与实际阅读范围](references/research/source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://link.springer.com/article/10.1007/s11229-024-04584-1">《逻辑研究》第二卷</a>，导论第 2 节；链接中的学术研究引述德文原句。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
