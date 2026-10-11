<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Wowblk/Wowblk/main/assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Wowblk/Wowblk/main/assets/header-light.svg">
  <img alt="Wowblk. Agent systems and backend engineering." src="https://raw.githubusercontent.com/Wowblk/Wowblk/main/assets/header-light.svg" width="960">
</picture>

I build the systems around AI agents: tool permissions, sandboxed execution, and context management.

关注 Agent 如何调用工具、管理上下文，以及在明确的执行边界内运行。

`Python` · `Java` · `Go` · `TypeScript`

## Selected work

### [TitanX](https://github.com/Wowblk/TitanX)

An agent framework with explicit execution boundaries. The Python SDK brings together tool authorization, policy controls, context compaction, audit logs, and sandbox backends.

[Code & architecture](https://github.com/Wowblk/TitanX#readme) · [Security model](https://github.com/Wowblk/TitanX/blob/main/SECURITY.md)

### [KnowFlow](https://github.com/Wowblk/KnowFlow)

A knowledge community with an AI assistant for finding content, organizing published posts, and creating drafts. Built with Spring Boot, React, a Go gateway, and TitanX.

[Code & setup](https://github.com/Wowblk/KnowFlow#readme)

### [video-bilingual-notes](https://github.com/Wowblk/video-bilingual-notes)

A Codex skill and Python helper for reading videos as bilingual documents. It keeps original transcripts, translations, timestamps, and screenshots together, with checks for source coverage.

[Install & examples](https://github.com/Wowblk/video-bilingual-notes#readme)

<details>
<summary>中文项目介绍</summary>

- **[TitanX](https://github.com/Wowblk/TitanX)** 是 Python Agent SDK / 框架，关注工具授权、上下文压缩、策略控制、审计和沙箱执行。
- **[KnowFlow](https://github.com/Wowblk/KnowFlow)** 是知识社区与 AI 助手项目，通过 Java 后端、Go gateway、React 前端和 TitanX 支持内容检索、整理与草稿创建。
- **[video-bilingual-notes](https://github.com/Wowblk/video-bilingual-notes)** 将视频整理为中英对照阅读文档，保留原文、时间戳与截图，并检查来源覆盖。

</details>

---

For questions, ideas, or bug reports, open an issue in the relevant project. 欢迎在项目仓库交流。
