## ADDED Requirements

### Requirement: Chapter 18 project performance domains must provide a plain-language note
第18章 `项目绩效域` 必须提供 `白话拆解.md`，用于把绩效域视角、八大绩效域、交付价值、度量与不确定性等最容易发虚的概念用更口语化、更贴近日常项目的方式讲清楚。

#### Scenario: Learner knows the names of the performance domains but still cannot explain them
- **Given** 学习者已经阅读第18章正式讲解材料
- **When** 他仍然觉得绩效域“名字记住了，但不知道到底在看什么”
- **Then** 能在 `chapters/18-项目绩效域/` 找到 `白话拆解.md`
- **And** 文档能用大白话、业务例子和记忆抓手解释这些概念

### Requirement: Chapter 19 configuration and change management must provide a plain-language note
第19章 `配置与变更管理` 必须提供 `白话拆解.md`，用于把配置项、基线、配置库、变更闭环、发布与回退等最容易混淆的高频概念用更口语化、更贴近日常项目的方式讲清楚。

#### Scenario: Learner can recite the steps but still mixes configuration and change control
- **Given** 学习者已经阅读第19章正式讲解材料
- **When** 他仍然分不清配置管理和变更管理分别在管什么
- **Then** 能在 `chapters/19-配置与变更管理/` 找到 `白话拆解.md`
- **And** 文档能用大白话、业务例子和记忆抓手解释这些概念

### Requirement: Chapters 18 and 19 plain-language notes must sit between scenario explanation and review questions
第18章和第19章的 `README.md` 学习入口中，如提供 `白话拆解.md`，必须将其放在 `过程场景讲解.md` 之后、`复盘题单.md` 之前，以体现“先建立正式理解，再结合业务场景，再用白话打通难点，最后主动回忆”的顺序。

#### Scenario: Learner follows the study order for chapter 18 or chapter 19
- **Given** 读者打开 `chapters/18-项目绩效域/README.md` 或 `chapters/19-配置与变更管理/README.md`
- **When** 他查看学习入口
- **Then** 会先看到 `过程场景讲解.md`
- **And** 接着看到 `白话拆解.md`
- **And** 之后才进入 `复盘题单.md`

