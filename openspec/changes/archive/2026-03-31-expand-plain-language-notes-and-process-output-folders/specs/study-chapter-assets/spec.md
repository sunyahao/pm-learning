## ADDED Requirements

### Requirement: Chapters 08 to 17 must provide plain-language study notes
第08章至第17章必须提供 `白话拆解.md`，用于把本章最容易发虚的高频概念用更口语化、更贴近日常项目的方式讲清楚。

#### Scenario: Learner knows the terms but still lacks mental models
- **Given** 学习者已经阅读正式整理、精讲或过程场景讲解
- **When** 他仍然觉得概念抽象、不会落到业务场景
- **Then** 能在对应章节找到 `白话拆解.md`
- **And** 文档能提供大白话解释、业务例子和一句话记忆

### Requirement: Chapters 08 to 17 README files must place plain-language notes before review prompts
第08章至第17章的 `README.md` 学习入口必须将 `白话拆解.md` 放在 `过程场景讲解.md` 之后、`复盘题单.md` 之前。

#### Scenario: Learner follows the default chapter study order
- **Given** 读者从第08章至第17章任一章节 `README.md` 开始学习
- **When** 他查看学习入口顺序
- **Then** 会先看到 `过程场景讲解.md`
- **And** 接着看到 `白话拆解.md`
- **And** 之后才看到 `复盘题单.md`

### Requirement: Core chapter output artifacts must be grouped under process folders
第08章至第17章以及第19章的 `输出物/` 目录必须按过程或步骤建立子目录，根目录 `README.md` 负责作为总索引，明确展示“哪个输出物属于哪个过程”。

#### Scenario: Learner wants to understand output artifacts through process ownership
- **Given** 学习者打开核心章节的 `输出物/README.md`
- **When** 他查看输出物索引
- **Then** 能按过程看到文件归属
- **And** 能进入对应过程子目录查看样例文件
