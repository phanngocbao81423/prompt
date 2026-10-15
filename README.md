# Prompt Skill

按使用场景分类的提示词库。[SKILL.md](SKILL.md) 是统一入口：根据任务选择合适的提示词，再读取对应的 Markdown 文件。

## 提示词目录

| 场景分类 | 提示词类型 | 适用任务 | 文件 |
| --- | --- | --- | --- |
| learning（学习与讲解） | 系统化讲解复杂概念 | 从零理解陌生概念，建立知识关联并检验理解 | [explain-complex-concepts.md](prompts/learning/explain-complex-concepts.md) |

## 整理规则

- 按使用场景在 `prompts/` 下分类，每种提示词类型使用一个 Markdown 文件。
- 文件名直观描述用途，例如 `explain-complex-concepts.md`；不添加版本后缀。
- 新增类型时，先选择合适的场景分类，再更新上方目录和根目录的 `SKILL.md`。
- 同一类型的内容改进直接编辑对应文件；需要区分用途时，新建名称清晰的类型文件。
