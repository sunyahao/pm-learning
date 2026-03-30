# AGENTS.md

本仓库以 OpenSpec 作为唯一规范源头。

## 开始前先看

1. 先阅读 `openspec/project.md`，了解项目范围、来源材料和仓库边界。
2. 在修改任何学习资产前，先阅读 `openspec/specs/` 下对应能力的规范。
3. 将 `chapters/` 视为派生内容；只有在规范明确后，才去更新章节文件。

## 必须遵守的流程

1. 任何新的结构调整或内容规则变更，都应在 `openspec/changes/<change-id>/` 下建立或更新 OpenSpec change。
2. 在 `proposal.md` 中写清为什么要改，在 `design.md` 中写清方案，在 `tasks.md` 中写清可核验任务，在 `specs/` 中记录规范增量。
3. 保持 `openspec/specs/` 中的当前规范与仓库实际状态一致。

## 项目专属规则

1. 主来源材料是 `高项-三色笔记.pdf`。
2. `chapters/` 目录必须与 PDF 目录保持 24 章一一对应。
3. 章节文件名和章节标题必须使用 PDF 原始章节名。
4. 生成的章节内容必须可追溯到 PDF，不允许未标注地把多个 PDF 章节合并成一个文件。
