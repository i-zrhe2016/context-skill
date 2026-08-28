# Context Efficiency Skill

`context-efficiency` 是一个 Codex skill，用于在长时间编码、检索和调试任务中减少无关上下文，同时保留用户约束、关键证据和可继续执行的状态。

仓库地址：[github.com/i-zrhe2016/context-skill](https://github.com/i-zrhe2016/context-skill)（公开仓库）。

## 安装

使用 Codex 自带的 GitHub 安装器：

```bash
python3 "${CODEX_HOME:-$HOME/.codex}/skills/.system/skill-installer/scripts/install-skill-from-github.py" \
  --repo i-zrhe2016/context-skill \
  --path context-efficiency
```

默认安装到 `${CODEX_HOME:-$HOME/.codex}/skills/context-efficiency`。安装完成后新开一轮 Codex，再使用 `$context-efficiency` 调用。

## 文档索引

- [使用与设计说明](docs/context-efficiency.md)
- [工作循环图（SVG）](docs/diagrams/context-efficiency-workflow.svg)
- [工作循环图（PNG）](docs/diagrams/context-efficiency-workflow.png)
- [工作循环图源文件（PlantUML）](docs/diagrams/context-efficiency-workflow.puml)
- [Skill 入口](context-efficiency/SKILL.md)
- [UI 元数据](context-efficiency/agents/openai.yaml)

## 校验

在 Codex 环境中可运行官方 skill 校验器：

```bash
python3 /root/.codex/skills/.system/skill-creator/scripts/quick_validate.py context-efficiency
```
