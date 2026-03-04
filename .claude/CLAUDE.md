# learning-ai-series

## 概述
通过 Claude + NotebookLM 自动生成结构化学习手册系列，采用"方法论 × 领域知识 = 可执行学习"的核心思路。

## 技术栈
Python、Markdown、NotebookLM API、Bash 脚本

## 目录结构
```
learning-ai-series/
├── skills/                 # 可发布的 Skill 定义
│   └── 如何学习/           # 主要 Skill
├── .git/                   # GitHub 仓库
├── README.md
└── docs/                   # 学习手册输出
```

## 开发规范
- Skill 安装命令：`mkdir -p ~/.claude/skills/如何学习 && curl -o ... `
- Markdown 格式需严格遵循 Skill 规范（prompt、examples、checklist）
- NotebookLM 链接格式：`https://notebooklm.google.com/notebook/xxx`
- commit message 英文，格式：`feat/fix/refactor: description`
- 发布前需在本地测试 Skill 调用

## 注意事项
- 仓库已在 GitHub 上，分支管理需谨慎
- 每个系列主题需准备两个 NotebookLM：A（方法论）和 B（领域知识）
- 输出手册通常为 6 章结构
- 与 claude-skills 仓库紧密关联
