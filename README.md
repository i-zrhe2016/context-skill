# Context Efficiency Skill

`context-efficiency` 是一个 Codex skill，用于在长时间编码、检索和调试任务中减少无关上下文，同时保留用户约束、关键证据和可继续执行的状态。

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
