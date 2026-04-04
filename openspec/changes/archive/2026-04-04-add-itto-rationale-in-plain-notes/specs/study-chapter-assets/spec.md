## ADDED Requirements

### Requirement: Chapters 08 through 17 must explain why their key ITTOs appear
第08章至第17章的 `白话拆解.md` 必须补充“为什么是这些 ITTO”的解释，帮助学习者把过程目标、项目动作和关键输入、关键工具与技术、关键输出物对应起来，而不是只机械背诵名称。

#### Scenario: Learner remembers ITTO names but cannot explain their logic
- **Given** 学习者已经看到某章的 ITTO 列表
- **When** 他仍然不知道为什么该过程会吃进这些输入、使用这些工具、产出这些输出
- **Then** 可在 `白话拆解.md` 中看到成因解释
- **And** 解释会把过程动作与关键输入、关键工具与技术、关键输出物联系起来

### Requirement: ITTO quick-view files should point back to plain-language rationale
第08章至第17章的 `ITTO输出速看.md` 应补充回链提示，引导学习者从快速记忆跳回 `白话拆解.md` 中对应的 ITTO 成因解释。

#### Scenario: Learner wants to go from memorizing names to understanding process logic
- **Given** 学习者正在查看某章的 `ITTO输出速看.md`
- **When** 他发现自己记住了名称但仍不理解为什么会这样配
- **Then** 能看到回链提示
- **And** 能直接回到该章 `白话拆解.md` 中对应的 ITTO 解释部分
