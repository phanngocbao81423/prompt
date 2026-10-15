# Prompt Skill

这是一个按用途分类的提示词仓库。每个提示词作为一个可独立调用的 Skill 保存，具体版本放在该 Skill 的 `prompts/` 目录中。

## 目录

| 分类 | Skill | 用途 | 当前版本 |
| --- | --- | --- | --- |
| learning（学习与讲解） | [explain-complex-concepts](skills/learning/explain-complex-concepts/SKILL.md) | 循序渐进地讲解陌生、复杂的概念 | [structured-concept-explanation-v1.md](skills/learning/explain-complex-concepts/prompts/structured-concept-explanation-v1.md) |

## 组织约定

- 按用途在 `skills/` 下分类；每个 Skill 单独建目录。
- `SKILL.md` 描述适用场景、调用方式，并指向当前采用的提示词版本。
- 原始提示词存放在该 Skill 的 `prompts/` 目录；新版本新增 Markdown 文件，不覆盖旧版本。
- 文件名说明具体用途，并以 `-v1.md`、`-v2.md` 等后缀标明版本；更新当前版本时同步修改 `SKILL.md` 和本目录。
