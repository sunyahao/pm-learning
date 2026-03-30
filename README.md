# gaoxiang-spec

这是一个基于 OpenSpec 管理的高项备考仓库。

## 仓库定位

- `openspec/` 是当前仓库的规范源头，保存正式规格、变更记录和 AI 协作约束。
- `chapters/` 是根据规格产出的派生学习资产，当前与 `高项-三色笔记.pdf` 保持 24 章一一对应，并按“每章一个目录”的方式组织。
- `guides/` 用于保存总览型备考策略、趋势分析和冲刺计划。
- `高项-三色笔记.pdf` 是当前版本的主来源材料。
- `2015-2024年高级历年真题合集/` 是论文、案例和选择题训练的正式真题来源。

## OpenSpec 结构

```text
.
|-- AGENTS.md
|-- openspec/
|   |-- config.yaml
|   |-- project.md
|   |-- specs/
|   |   |-- study-repository/
|   |   |   `-- spec.md
|   |   |-- source-alignment/
|   |   |   `-- spec.md
|   |   |-- study-chapter-assets/
|   |   |   `-- spec.md
|   |   `-- assistant-workflow/
|   |       `-- spec.md
|   `-- changes/
|       `-- archive/
`-- chapters/
    |-- index.md
    `-- 01..24 各章节目录
`-- guides/
    `-- 备考策略与趋势分析
```

## 使用说明

1. 修改仓库前先看 [AGENTS.md](/D:/codex-project/AGENTS.md)。
2. 了解项目边界和来源时看 [openspec/project.md](/D:/codex-project/openspec/project.md)。
3. 需要确认“现在系统应该是什么样”时看 `openspec/specs/`。
4. 需要追溯“为什么会这样设计”时看 `openspec/changes/archive/`。
5. 需要直接复习时看 [chapters/index.md](/D:/codex-project/chapters/index.md)。
6. 需要先判断“现在该看哪类资料最提分”时看 [guides/资料盘点与提分优化建议.md](/D:/codex-project/guides/资料盘点与提分优化建议.md)。

## 当前约定

- OpenSpec 规范是源头，章节内容是派生结果。
- 章节数量、顺序和标题与 PDF 目录保持一致，不再做聚合映射。
- `高项-三色笔记.pdf` 管章节主线，历年论文/案例/选择题真题管题型趋势和训练依据。
- 每章目录至少包含 `README.md`、`主脉络.md` 和 `案例/` 目录。
- 第08章至第17章以及第19章额外包含 `输出物/` 目录，用于存放关键输出物样例。
- 如果后续继续扩展内容，应先补 OpenSpec change，再同步更新派生学习资产。
