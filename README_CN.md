# CLI Proxy API 管理中心 — Ai-Data-Man 维护分支

本仓库是 [router-for-me/Cli-Proxy-API-Management-Center](https://github.com/router-for-me/Cli-Proxy-API-Management-Center) 的 **维护分支**。

上游项目是通过 Management API 管理与排查 CLI Proxy API 的单文件 Web UI（React + TypeScript），支持配置、凭据与日志管理。

## 我们的改动

- **CI/CD**：增加 `workflow_dispatch` 和 `release/edited` 触发方式；增强发布流程附带 SHA256 摘要
- **使用量统计**：**恢复**"使用统计"功能页面及相关组件（上游自 v6.10.0 起移除）
- **修复与维护**：UI 样式优化、OpenAI 提供商卡片修复、构建工具链升级、依赖更新

## 文档

完整功能文档和使用指南请参见上游：

- [router-for-me/Cli-Proxy-API-Management-Center](https://github.com/router-for-me/Cli-Proxy-API-Management-Center) — 原始仓库
- [CLIProxyAPI 用户手册](https://help.router-for.me/cn/) — 官方指南

## 相关 Fork

- [Ai-Data-Man/CLIProxyAPI](https://github.com/Ai-Data-Man/CLIProxyAPI) — CLIProxyAPI fork（恢复使用统计后端）
- [Ai-Data-Man/CLIProxyAPI-Tray](https://github.com/Ai-Data-Man/CLIProxyAPI-Tray) — Windows 托盘管理工具 fork

## 许可证

MIT
