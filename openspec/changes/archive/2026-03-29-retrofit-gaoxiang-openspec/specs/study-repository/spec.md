## 新增要求

### 要求：仓库必须具备标准 OpenSpec 结构
仓库必须暴露标准 OpenSpec 结构，至少包括根目录 `AGENTS.md`、`openspec/config.yaml`、`openspec/project.md`、`openspec/specs/` 和 `openspec/changes/`。

#### 场景：检查仓库根目录
- **前提** 贡献者打开仓库根目录
- **当** 他查看顶层文件和目录
- **则** 能看到根目录的 `AGENTS.md`
- **并且** 能看到 `openspec/config.yaml`
- **并且** 能看到 `openspec/project.md`
- **并且** 能看到 `openspec/specs/`
- **并且** 能看到 `openspec/changes/`

### 要求：必须区分规范源头和派生资产
仓库必须将 `openspec/specs/` 视为规范源头，并将 `chapters/` 视为遵循规范生成或维护的派生学习资产。

#### 场景：判断哪个目录是源头
- **前提** 贡献者需要确认仓库行为由谁定义
- **当** 他比较 `openspec/specs/` 与 `chapters/`
- **则** 能确认 `openspec/specs/` 是规范源头
- **并且** 能确认 `chapters/` 是派生输出层

### 要求：OpenSpec 规范文档必须使用中文
位于 `openspec/` 下的规范性文档必须使用中文编写。

#### 场景：检查规范语言
- **前提** 贡献者查看 `openspec/` 下的规范文档
- **当** 他阅读正文
- **则** 正文内容使用中文
