## ADDED Requirements

### Requirement: Chapter 10 schedule management must provide a plain-language note
第10章 `进度管理` 必须提供 `白话拆解.md`，用于用更口语化、更贴近日常项目业务的方式讲解 `FS/SS/FF/SF`、`PDM/ADM`、`提前量/滞后量`、`关键路径` 等高频难点。

#### Scenario: Learner understands the terms literally but still cannot use them
- **Given** 学习者已经阅读第10章正式讲解材料
- **When** 他仍然觉得进度逻辑“字面看得懂、业务里不会用”
- **Then** 能在 `chapters/10-进度管理/` 找到 `白话拆解.md`
- **And** 文档能用大白话、业务例子和记忆抓手解释这些概念

### Requirement: Plain-language notes must sit between scenario explanation and review questions
当某个章节提供 `白话拆解.md` 时，其 `README.md` 学习入口必须将它放在 `过程场景讲解.md` 之后、`复盘题单.md` 之前。

#### Scenario: Learner follows the chapter study order
- **Given** 读者从章节 `README.md` 开始学习
- **When** 该章节提供 `白话拆解.md`
- **Then** 读者会先看到 `过程场景讲解.md`
- **And** 再看到 `白话拆解.md`
- **And** 之后才进入 `复盘题单.md`
