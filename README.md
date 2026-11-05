# 网页制作

本仓库收录适用于 Codex 的网页制作技能，与 `medical-ppt-lab` 并列。

## 已安装技能

- [设计](.agents/skills/设计/SKILL.md)：基于 [pbakaus/impeccable](https://github.com/pbakaus/impeccable)，面向网页与界面设计，含 24 个设计命令。使用 Codex 时可通过 `$设计` 调用。
- [code简短](.agents/skills/code简短/SKILL.md)：基于 [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail)，引导编码任务优先复用现有实现并控制改动范围。可通过 `$code简短` 调用。

## 说明

技能文件采用 Agent Skills 格式，放在 `.agents/skills/`。Impeccable 上游包含额外参考资料与运行脚本；本仓库当前收录其技能入口文件，完整脚本支持请按上游说明安装。技能内容与更新以各自来源仓库为准。