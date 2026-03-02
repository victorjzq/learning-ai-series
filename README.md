# Learning AI Series

> 用最强方法论（A）× 最强领域知识（B）= 可执行学习手册（C）

## 核心思路

把学习拆成两个独立笔记本：
- **Notebook A**：方法论（如何学习任何东西）
- **Notebook B**：领域知识（想学的具体内容）

通过 Claude + NotebookLM 自动提炼，生成结构化学习手册。

## 工作流

```
Notebook A（方法论）
       ×
Notebook B（AI领域知识）
       ↓
Claude Skill 自动提问 + 整合
       ↓
6章可执行学习手册
```

## 使用方式

1. 准备 Notebook A：上传你的方法论资料到 NotebookLM
2. 准备 Notebook B：上传目标领域资料到 NotebookLM
3. 在 Claude Code 终端运行：

```bash
claude "调用如何学习skill，Notebook B链接：[你的链接]，主题：[主题]"
```

## Skill 安装

```bash
mkdir -p ~/.claude/skills/如何学习
curl -o ~/.claude/skills/如何学习/SKILL.md \
  https://raw.githubusercontent.com/victorjzq/learning-ai-series/main/skills/如何学习/SKILL.md
```

## 系列内容

| # | 主题 | 状态 |
|---|------|------|
| 01 | AI学习方法论 | 进行中 |

---
Built with Claude + NotebookLM
