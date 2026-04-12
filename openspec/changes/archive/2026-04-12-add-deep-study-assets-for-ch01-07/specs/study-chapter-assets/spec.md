## ADDED Requirements

### Requirement: Foundation chapters 01 through 07 must provide deep study assets
第01章至第07章的章节目录下必须提供 `完整整理.md`、`精讲.md`、`过程场景讲解.md`、`白话拆解.md`、`记忆与复盘/复盘题单.md` 和 `记忆与复盘/参考作答.md`，用于把信息化背景、技术基础、治理、系统管理、系统工程、项目管理概论和立项逻辑串成完整学习链。

#### Scenario: Learner wants to build a solid bridge before entering the knowledge domains
- **Given** 学习者正在系统复习第01章至第07章
- **When** 他进入任一前七章目录
- **Then** 能找到 `完整整理.md`
- **And** 能找到 `精讲.md`
- **And** 能找到 `过程场景讲解.md`
- **And** 能找到 `白话拆解.md`
- **And** 能在 `记忆与复盘/` 下找到 `复盘题单.md` 和 `参考作答.md`

### Requirement: Foundation chapters 01 through 07 should provide a memory and review bundle entry
第01章至第07章的章节目录下应提供 `记忆与复盘/README.md`，用于把 `核心记忆.md`、`记忆与复盘/复盘题单.md` 和 `记忆与复盘/参考作答.md` 汇总为统一入口。

#### Scenario: Learner wants to switch quickly between memorization and self-testing
- **Given** 学习者进入第01章至第07章任一章节目录
- **When** 他只想集中使用速记和复盘材料
- **Then** 能找到 `记忆与复盘/README.md`
- **And** 能从该入口快速进入 `核心记忆.md`、`复盘题单.md` 和 `参考作答.md`

### Requirement: Foundation chapter learning entries must introduce explanation before review
第01章至第07章的 `README.md` 学习入口中，`完整整理.md`、`精讲.md`、`过程场景讲解.md` 和 `白话拆解.md` 必须位于 `复盘题单.md` 之前，`参考作答.md` 必须位于 `复盘题单.md` 之后。

#### Scenario: Learner follows the study order from a foundation chapter README
- **Given** 读者打开第01章至第07章任一章节目录下的 `README.md`
- **When** 他查看学习入口
- **Then** 能先看到 `完整整理.md` 和 `精讲.md`
- **And** 在 `复盘题单.md` 之前看到 `过程场景讲解.md` 和 `白话拆解.md`
- **And** 在 `复盘题单.md` 之后看到 `参考作答.md`
