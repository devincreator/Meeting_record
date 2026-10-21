# Meeting_record｜中文研究型会议纪要 Skill + OpenSpec

本仓库将中文会议纪要的写作经验沉淀为可复用的 **Skill**、**OpenSpec 验收规范**、质量检查清单与空白模板。适用于公司调研、机构访谈、学术报告、工业技术大会等文本。

## 使用入口

- [SKILL.md](SKILL.md)：操作步骤、专业纠错、信息完整性、写作和 Word 交付标准。
- [openspec/config.yaml](openspec/config.yaml)：OpenSpec 项目约束。
- [openspec/specs/meeting-minutes/spec.md](openspec/specs/meeting-minutes/spec.md)：规范要求及 WHEN/THEN 验收场景。
- [references/quality-checklist.md](references/quality-checklist.md)：交付前逐项检查。
- [templates/meeting-minutes.md](templates/meeting-minutes.md)：两层结构的空白会议纪要模板。

## 工作方式

1. 提供原始访谈、录音转写或已获授权的文件，明确日期和机构；如果包含不同场次，先拆分。
2. 读取 [SKILL.md](SKILL.md)；按主题建立覆盖底稿，核对所有关键数字、专业术语及项目进度。
3. 生成“核心要点”（默认不超过 **5** 条）和“详细纪要”（默认不超过 **9** 节）。数量上限**不等于删减细节**。
4. 只整理用户指定材料，不自行补充年报、网络数据、投资观点或“注意事项”。用直接的结论式自然段，不保留问答、口语或“公司认为/交流中提到”。
5. 如需 Word，使用全黑字体、无段首方点，并核验实际文件及排版后交付。

## 范围和边界

本仓库只保存**通用工作规范及空白模板**，不保存原始访谈、会议录音、未公开业绩或完整私密纪要。需要外部事实核验时，应由使用者在具体任务中明确授权。

将 Skill 文件放在 GitHub **不代表自动安装**到 ChatGPT 或其他 AI 工具。使用前需让助手读取本仓库的 SKILL.md 与 OpenSpec 规范，或在支持 Skills 的工作环境中安装。

## 规范版本

v1.0.0｜2026-10-21
